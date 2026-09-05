# 📊 Automated Daily Sales & KPI Reporting Pipeline

An automated Python data pipeline that extracts product and sales metrics from an e-commerce API, calculates business-critical KPIs, and generates a formatted, multi-sheet daily Excel report.

## 🚀 Key Features
- **Automated Data Ingestion:** Fetches real-time transactional and product data via REST APIs using `requests`.
- **Data Transformation & Cleaning:** Normalizes nested JSON fields, computes estimated sales volume, and handles schema structuring using `pandas`.
- **KPI Aggregation:** Computes key operational metrics (Total Revenue, Catalog Size, Average Price, Category-wise Performance).
- **Automated Export:** Exports clean, multi-sheet analytical reports via `openpyxl`.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, Requests, OpenPyXL, Google Colab
