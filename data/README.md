Data
Dataset: Bank Customer Churn (DS3000 dataset pool #13) Source: https://www.kaggle.com/datasets/santoshd3/bank-customers (free Kaggle login required)

Download the CSV from the Kaggle page above.
Place it in this folder as Churn_Modelling.csv (the notebook also accepts Churn_Modeling.csv).
Expected: 10,000 rows x 14 columns, target column Exited.
split_assignment.csv is the frozen train/validation/test split (keyed by CustomerId). It is committed so every stage reuses exactly the same split. Do not regenerate it.
