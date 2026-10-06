# Credit-Risk-Analysis
This project focuses on predicting the probability of customer default using machine learning techniques. The goal is to analyze credit behavior, handle outliers, perform feature engineering, and build robust classification models to assess financial risk.

📊 Dataset Overview
Records: 149,173
Features: 11
Target Variable: SeriousDlqin2yrs (1 = Default, 0 = No Default)
The dataset contains information about customer credit utilization, delinquency history, income, debt ratio, and more.

🔍 Exploratory Data Analysis (EDA)
Key steps:

Identified skewed distributions and outliers
Visualized delinquency patterns
Analyzed correlations between features and default risk
Used boxplots and histograms for insights
🛠️ Data Preprocessing
Outlier treatment using domain-based capping
Log transformation for highly skewed variables (e.g., DebtRatio)
Missing value handling using SimpleImputer
Feature scaling using StandardScaler
Used ColumnTransformer for structured preprocessing
🤖 Models Implemented
Model	ROC-AUC
Logistic Regression	0.855
Gradient Boosting	0.830
Additional models explored:

Decision Tree
Random Forest
📈 Evaluation Metrics
ROC-AUC
Accuracy
Recall
F1 Score
Confusion Matrix
🧰 Technologies Used
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
📁 Project Structure
About
No description, website, or topics provided.
Resources
Readme
Activity
Stars
0 stars
Watchers
0 watching
Forks
0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
1
 (1)
@Attracy
AttracyShashank_Attracy
Languages
Jupyter Notebook
100%
Footer
