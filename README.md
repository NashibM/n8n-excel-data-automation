# n8n-excel-data-automation
End-to-end cloud data automation using n8n, Excel, and OneDrive
# n8n Excel Data Automation Pipeline

## Project Overview
This project demonstrates an end-to-end cloud-based data automation pipeline using **n8n**, **Excel**, and **OneDrive**.

Unlike traditional BI automation that starts at visualization, this project automates the entire data preparation workflow.

---

## Architecture
Schedule Trigger → OneDrive → Data Extraction → Business Logic → Excel Generation → OneDrive → Dashboard

---

## Workflow Steps
1. Scheduled trigger runs automatically
2. Downloads Excel file from OneDrive
3. Extracts structured data
4. Applies transformation logic using JavaScript
5. Converts processed data back to Excel
6. Uploads final Excel file to cloud storage

---

## Tools Used
- n8n (Workflow orchestration)
- OneDrive (Cloud storage)
- Excel (Data storage & dashboard)
- JavaScript (Business logic)

---

## Why This Project Is Different
- Automates data pipeline, not just dashboards
- Tool-agnostic design (Power BI optional)
- Cloud-first architecture
- Scalable and reusable workflow

---

## Use Case
Ideal for automating recurring reports, operational dashboards, and data preparation pipelines.

---

## Author
Nashib M
