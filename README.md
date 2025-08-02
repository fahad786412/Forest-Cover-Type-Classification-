Project Title: Forest Cover Type Classification
Objective:
To predict the forest cover type based on cartographic and environmental features using tree-based machine learning models.

Dataset:
The Covertype dataset from UCI Machine Learning Repository, which contains over 500,000 observations and 54 features, including elevation, slope, soil type, and wilderness area indicators.

Workflow:

Data Preprocessing:

Loaded the dataset and assigned meaningful column names.

Transformed target labels from 1–7 to 0–6 for compatibility with XGBoost.

Split the data into training and testing sets using stratified sampling.

Model Training & Evaluation:

Trained a Random Forest Classifier and an XGBoost Classifier for multi-class classification.

Evaluated both models using accuracy score, confusion matrix, and classification report.

Visualized the top 15 most important features for both models.

Model Comparison:

Compared performance between Random Forest and XGBoost in terms of accuracy and feature importance.

XGBoost showed slightly better performance and interpretability.

Hyperparameter Tuning (Bonus):

Performed GridSearchCV on the Random Forest model to optimize n_estimators, max_depth, and min_samples_split.

Tools & Libraries:
Python, Pandas, Matplotlib, Seaborn, Scikit-learn, XGBoost
