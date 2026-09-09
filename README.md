# Salam Odeh
### Senior Data Engineer · Ramallah, Palestine · Open to remote

12 years building data systems at Bank of Palestine, ETL pipelines, enterprise BI, and a Snowflake cloud migration. I shipped an ML-powered cheque verification system processing 10,000+ documents daily and automated 80% of manual reporting workflows. Recently built a complete cloud-native data pipeline from scratch with dlt, dbt, and DuckDB, including diagnosing and fixing a real security incident along the way.

---

## Stack

**Core:** SQL · Python · Snowflake · Azure Data Factory · Oracle Data Integrator  
**Data Engineering:** dbt · dlt · DuckDB · Git · GitHub Actions  
**BI:** Power BI · Looker Studio · OBIEE · SAP BO  
**ML:** OpenCV · Scikit-learn · Pandas · Keras

---

## Key projects

**Olist e-commerce data pipeline**  
End-to-end cloud-native pipeline: dlt ingestion (CSVs + 2 live APIs) → DuckDB → dbt (9 models, 21 tests) → daily GitHub Actions automation → public dashboard. Includes a real production lesson, found and fully remediated an exposed cloud credential, with complete git history cleanup.  
[Code](https://github.com/salamodeh/olist-data-pipeline) · [Live dashboard](https://datastudio.google.com/reporting/bdc37536-654b-44c0-80a6-ad0e2796684a/page/X2b1F)

**Prediction of product sales**
End-to-end CRISP-DM project on 8,523 retail product-outlet records. A tuned Random Forest regression explains 60% of sales variance (R² = 0.597, ±$734 MAE), and a companion classification model flags high-sellers at 81% accuracy / 87% recall. `Item_MRP` and `Outlet_Type` are the two strongest, triple-validated drivers of sales.
[Code](https://github.com/salamodeh/prediction-of-product-sales-project)

**Car insurance claim prediction**
Classification project predicting auto insurance claims from driving history, demographics, and vehicle data (10,000 policyholders). Compared a baseline Random Forest, a PCA + clustering engineered Random Forest, and a Keras neural network, all within 1.5 F1 points of each other, with the engineered Random Forest recommended for production. Includes a fairness check confirming the model doesn't lean on race, gender, or age.
[Code](https://github.com/salamodeh/car-insurance-claim-prediction)

**On-premise Oracle to Snowflake migration**  
Contributed as part of a cross-functional team to migrate Bank of Palestine's on-premise data warehouse to Snowflake, re-mapped ETL workflows from Oracle Data Integrator, validated migrated data, and supported performance tuning across 500+ downstream reports.

**Cheque verification system**  
Computer vision model (Python, OpenCV) processing 10,000+ cheques/day in production. Reduced manual review by 80% and strengthened fraud controls.

**Cash management analytics**  
ETL pipelines + Power BI dashboards for treasury decision-making at Bank of Palestine. Reduced excess cash holdings across branches.

---

## Currently

- Learning: AI-assisted development with OpenCode.ai, BigQuery
- Open to: remote Data Engineer / Analytics Engineer roles

---

📧 salam.odeh3@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/salam-odeh-93068a62/)  
🌐 [Portfolio](https://salamodeh.github.io)
