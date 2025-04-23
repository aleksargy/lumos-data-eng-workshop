# 🏥 Medallion Architecture - Healthcare Data Pipeline

This notebook is part of a practical data engineering workshop at **Lumos**. You’ll simulate the role of a **data engineer** helping a healthcare provider make sense of their data using a structured pipeline.

We’ll use synthetic healthcare data generated with [Synthea](https://synthea.mitre.org), including patient records, medical encounters, and prescribed medications.

---

## 🎯 Objective

Simulate the building of a pipeline in .ipynb that follows the **Medallion Architecture** pattern to:

- Load and inspect raw datasets
- Clean and standardise the data
- Join tables to create enriched records
- Compute KPIs (Key Performance Indicators)
- Generate visualizations to support reporting

---

## 🧱 Architecture Layers

- **🥉 Bronze Layer**: Raw data directly from the source, no transformations applied.
- **🥈 Silver Layer**: Cleaned, normalised, and joined data ready for analysis.
- **🥇 Gold Layer**: Aggregated data and KPIs, used for insights and visualizations.

---

## 💡 What You'll Practice

- "Realistic" data exploration and cleaning
- Transforming messy medical records
- Joining multiple sources with business logic
- Aggregating KPIs
- Plotting results using `matplotlib`

---