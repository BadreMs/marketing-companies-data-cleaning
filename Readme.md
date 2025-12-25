## Marketing Campaign Data Cleaning & Data Quality

This project demonstrates an end-to-end data cleaning and data quality validation workflow applied to a messy marketing campaigns dataset.

Using Python and pandas, the pipeline focuses on improving data reliability through:
- Type normalization and currency parsing
- Categorical standardization and typo correction
- Boolean normalization
- Date parsing and temporal consistency checks
- Business rule enforcement (clicks vs impressions)
- Outlier handling using winsorization
- Feature extraction from text fields

A data quality layer is implemented to track before/after metrics, log applied rules, and generate a structured data quality report, ensuring transparency and reproducibility of the cleaning process.



