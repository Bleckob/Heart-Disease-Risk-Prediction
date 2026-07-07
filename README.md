Medical Heart Risk Prediction using XGBoost

An airtight machine learning pipeline built to predict clinical heart disease risk with 83.61% accuracy using the UCI Heart Disease dataset.

Key Achievements & Core Competencies
Advanced Data Pipeline Construction:Designed an isolated preprocessing engine using `ColumnTransformer` to handle numerical and categorical features independently, protecting the model from target leakage.
Complex Bug Diagnosis (Data Alignment):Successfully tracked down and resolved a critical unpacking misalignment error within `train_test_split`, diagnosing why feature matrices were bleeding into the target vector.
Categorical Encoding Strategy: Implemented One-Hot Encoding for categorical string identifiers (e.g., `thal`) to systematically break non-ordinal data into unbiased features for XGBoost tree structures.
Clinical Metric Evaluation:Achieved a balanced evaluation workflow, focusing heavily on the critical real-world medical trade-off between Precision (73%) and Recall (65%) to understand clinical risk.

Tech Stack & Tools Used
Language: Python
Libraries: Scikit-Learn, XGBoost, Pandas, NumPy
Environment: Google Colab
