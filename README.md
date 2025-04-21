# 🏥 Medallion Architecture - Healthcare Data Pipeline

This notebook is part of a practical data engineering workshop at **Lumos**, a student-run data consulting community. You’ll simulate the role of a **data engineer** helping a healthcare provider make sense of their data using a structured pipeline.

We’ll use synthetic healthcare data generated with [Synthea](https://synthea.mitre.org), including patient records, medical encounters, and prescribed medications.

---

## 🎯 Objective

Build a pipeline that follows the **Medallion Architecture** pattern to:

- Load and inspect raw datasets
- Clean and standardize the data
- Join tables to create enriched records
- Compute KPIs (Key Performance Indicators)
- Generate visualizations to support reporting

---

## 🧱 Architecture Layers

- **🥉 Bronze Layer**: Raw data directly from the source, no transformations applied.
- **🥈 Silver Layer**: Cleaned, normalized, and joined data ready for analysis.
- **🥇 Gold Layer**: Aggregated data and KPIs, used for insights and visualizations.

---

## 📁 Folder Structure
bronze/ # Raw input CSVs (patients.csv, encounters.csv, medications.csv) 
silver/ # Cleaned and transformed tables 
gold/ # KPI results and charts notebook.ipynb

## 💡 What You'll Practice

- Realistic data exploration and cleaning
- Transforming messy medical records
- Joining multiple sources with business logic
- Aggregating KPIs:
  - Average number of encounters per patient
  - Top 5 encounter reasons
  - Medication usage by age group
- Plotting results using `matplotlib`

---

## 🚀 How to Run

1. Make sure you have Python 3 installed.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib numpy
3.Open notebook.ipynb and follow along with the step-by-step challenges.

---

## 👩‍💻 About Lumos
Lumos is a student-driven data consulting initiative focused on learning by doing. We work on real projects, run hands-on workshops, and help each other grow. ✨
