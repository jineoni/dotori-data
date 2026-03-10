# Dotori-Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

A data processing and modeling repository for the Dotori college admission platform. This project automates the extraction of university statistics from unstructured PDFs and builds analytical models to calculate student-to-school compatibility.

---

## Related Repositories
* **Frontend:** [dotori-frontend](https://github.com/lukasp-dev/dotori-web)
* **Backend:** [dotori-backend](https://github.com/lukasp-dev/dotori-backend)
* **AI Server:** [dotori-fastapi](https://github.com/lukasp-dev/dotori-fastapi)
* **Data:** [dotori-data](https://github.com/jineoni/dotori-data)

---

## Tech Stack & Methodology
* **Python (pdfplumber, Pandas):** Automated crawling, extraction, and structuring of official university PDF reports and Common Data Sets (CDS).
* **Data Pipelines:** Transformed raw PDF text and tables into organized datasets for 100+ universities.
* **Scoring Logic:** Developed mathematical models (in Jupyter Notebooks) to evaluate admission probabilities based on structured data.

---

## Repository Structure

```text
dotori-data/
├── data/
│   ├── raw/             # Raw university PDF documents and CDS reports
│   └── outputs/         # Processed datasets extracted from CDS
├── notebooks/           # Jupyter notebooks for PDF parsing and model development
├── config.txt           # Configuration settings for data pipelines
├── scoring.txt          # Weights and logic definitions for the recommendation engine
└── README.md            # Project documentation
```
