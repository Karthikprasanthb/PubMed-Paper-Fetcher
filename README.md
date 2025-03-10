# PubMed-Paper-Fetcher
# PubMed Paper Fetcher

A Python script to fetch research papers from PubMed and export them to CSV.

## 🚀 Features

✅ Fetches research papers using PubMed API\
✅ Filters for non-academic authors with biotech affiliations\
✅ Saves results in CSV format\
✅ Provides command-line options for flexibility\

---

🛠️ Installation

1. Clone the Repository

```bash
git clone <repository-URL>
cd PubMed-Paper-Fetcher
```

2. Install Dependencies

```bash
pip install requests
```

---

📋 Usage

To fetch papers and save them as CSV:

```bash
python new.py "your search query" -f output.csv
```

For example:

```bash
python new.py "cancer treatment" -f cancer_papers.csv
```

Command-line Options

- `-f` or `--file` : Specify the filename for the CSV output.
- `-d` or `--debug` : Enable debug mode for detailed execution steps.

---

🔍 Example Output

| PubmedID | Title         | Publication Date | Non-academic Author(s) | Company Affiliation(s) | Corresponding Author Email                   |
| -------- | ------------- | ---------------- | ---------------------- | ---------------------- | -------------------------------------------- |
| 12345678 | Example Title | 2025-03-01       | John Doe               | XYZ Biotech Inc.       | [john.doe@xyz.com](mailto:john.doe@xyz.com) |

---

 🧪 Testing

To run tests for the project:

```bash
pytest test_pubmed.py
```



