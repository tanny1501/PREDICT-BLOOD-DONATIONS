# PREDICT-BLOOD-DONATIONS
Forecasting blood donations using machine learning on the UCI Blood Transfusion Dataset. This project applies EDA, TPOT AutoML, and Logistic Regression to predict repeat donors, helping hospitals and blood banks plan drives, reduce shortages, and ensure timely blood supply.
<br>
<br>
<br>
Project Overview:

This project was developed during my internship with MedTourEasy (New Delhi). Using the Blood Transfusion Service Center Dataset (UCI Repository, 748 donor records), the goal was to build a predictive model that identifies potential repeat donors.
<br>
<br>
<br>
Methodology:

Data Preprocessing: Cleaned and normalized features to handle imbalance and variance.

Exploratory Data Analysis (EDA): Explored donor patterns, correlations, and class imbalance (76% non-donors vs. 24% repeat donors).

Model Selection: Used TPOT AutoML for automated pipeline optimization.

Model Training: Logistic Regression was selected as the best model.

Evaluation: Achieved an ROC-AUC score of 0.7891, showing strong predictive performance.
<br>
<br>
<br>
Key Insights:

Frequency of donations strongly correlates with total volume donated.

Logistic Regression provided both interpretability and accuracy.

Addressing feature variance (log normalization) improved performance.
<br>
<br>
<br>
Tech Stack:

Python: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, TPOT

Google Colab: Cloud-based environment with GPU/TPU support
