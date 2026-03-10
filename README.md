# 🐿️ Dotori-Data

> **Equal Opportunities for Students at a Fair Price.** Smart data. Honest metrics. Real opportunity.

---

## 🔗 Repositories
* **Frontend:** [dotori-frontend](https://github.com/lukasp-dev/dotori-web)
* **Backend:** [dotori-backend](https://github.com/lukasp-dev/dotori-backend)
* **AI Server:** [dotori-fastapi](https://github.com/lukasp-dev/dotori-fastapi)
* **Data:** [dotori-data](https://github.com/jineoni/dotori-data)

---

## 💡 Why Dotori-Data?
Strategic college admissions require access to the **Common Data Set (CDS)**—the gold standard of university statistics. However, these reports are often buried in complex PDF files across thousands of university websites.

**Dotori-Data** serves as the intelligence layer of the platform. We automate the extraction and analysis of this critical information, converting unstructured PDF reports into clean, structured datasets. This data powers our recommendation engines, ensuring students have access to accurate admission probabilities and school profiles.

---

## ✨ Features
* **PDF Data Extraction** – Automated crawling and parsing of official university PDF documents and Common Data Sets (CDS).
* **Structured Data Pipelines** – Transforming raw PDF information into organized JSON and CSV formats for 100+ universities.
* **Admission Scoring Logic** – Developing and refining the mathematical models used to calculate student-to-school compatibility.
* **Database Management** – Maintaining foundational records for university profiles, including tuition, acceptance rates, and standardized test trends.

---

## 🛠 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

---

## 🗂️ Project Structure

```text
dotori-data/
├── data/
│   ├── raw/                # Raw university PDF documents and CDS reports
│   └── outputs/            # Processed datasets extracted from CDS
├── notebooks/
│   ├── pdf_crawling.ipynb  # Automated PDF crawling and parsing
│   └── modeling.ipynb      # School matching and scoring model development
├── config.txt              # Configuration settings for data pipelines
├── scoring.txt             # Weights and logic definitions for the recommendation engine
└── README.md               # Project documentation
```
