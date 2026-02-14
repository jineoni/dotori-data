# 🐿️ Dotori-Data

**Equal Opportunities for Students at a Fair Price.** Smart data. Honest metrics. Real opportunity.

---

## Repositories
* **Frontend:** [dotori-frontend](https://github.com/lukasp-dev/dotori-web)
* **Backend:** [dotori-backend](https://github.com/lukasp-dev/dotori-backend)
* **AI Server:** [dotori-fastapi](https://github.com/lukasp-dev/dotori-fastapi)
* **Data:** [dotori-data](https://github.com/jineoni/dotori-data)

---

## Why Dotori-Data?
Strategic college admissions require access to the **Common Data Set (CDS)**—the gold standard of university statistics. However, these reports are often buried in complex PDF files across thousands of university websites.

**Dotori-Data** serves as the intelligence layer of the platform. We automate the extraction and analysis of this critical information, converting unstructured PDF reports into clean, structured datasets. This data powers our recommendation engines, ensuring students have access to accurate admission probabilities and school profiles.

---

## Features
* **PDF Data Extraction** – Automated crawling and parsing of official university PDF documents and Common Data Sets (CDS).
* **Structured Data Pipelines** – Transforming raw PDF information into organized JSON and CSV formats for 100+ universities.
* **Admission Scoring Logic** – Developing and refining the mathematical models used to calculate student-to-school compatibility.
* **Database Management** – Maintaining foundational records for university profiles, including tuition, acceptance rates, and standardized test trends.

---

## Tech Stack
* **Language:** Python
* **Analysis & Modeling:** Jupyter Notebooks, Pandas, NumPy
* **Environment:** Anaconda
* **Data Sources:** University Common Data Sets (CDS), official PDF reports

---

## 🗂️ Project Structure

```text
dotori-data/
├── output_cds/             # Processed datasets extracted from Common Data Sets (v1-v4)
├── pdf/                    # Raw university PDF documents and CDS reports (v1-v4)
├── anaconda_projects/db    # Database environment and configuration setups
├── pdf_crawling.ipynb      # Main notebook for automated PDF crawling and parsing
├── modeling.ipynb          # Notebook for developing the school matching and scoring model
├── scoring.txt             # Weights and logic definitions for the recommendation engine
├── config.txt              # Configuration settings for data pipelines
└── README.md               # Project documentation
