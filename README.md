# 2025-Y2-S1-MLB-B3G2-06----Student-Depression-Prediction---Data-Preprocessing-EDA-Pipline
Group No: 2025-Y2-S1-MLB-B3G2-06

Data Preprocessing Pipeline 

Project Overview
This project focuses on preparing the Depression Dataset for machine learning tasks. Mental health data often contains missing values, imbalances, categorical survey responses, and sensitive variations that require careful preprocessing before model training.
Our team has collaboratively designed a structured data preprocessing pipeline in Google Colab using Python. The pipeline ensures the dataset is clean, consistent, unbiased, and ready for building predictive models to assist in early detection and analysis of depression-related patterns.

Objectives
•	Improve data quality for reliable depression prediction models.
•	Handle missing values, outliers, and duplicates common in mental health surveys.
•	Convert categorical responses (e.g., Yes/No, Likert scales) into machine-readable formats.
•	Balance the dataset to ensure fair learning across depressed and non-depressed groups.
•	Engineer new features that capture hidden relationships (e.g., stress ratios, lifestyle interactions).
•	Prepare a final dataset optimized for machine learning pipelines.

Dataset Details – Depression Dataset
•	Contains survey responses and demographic details related to mental health and depression.
•	Features include:
o	Demographics: Age, Gender, Occupation, etc.
o	Lifestyle & Health Factors: Sleep patterns, exercise, diet, medication, etc.
o	Mental Health Indicators: Anxiety levels, stress levels, previous diagnoses, treatment history.
•	Target Variable: Depression Status (binary classification: Depressed / Not Depressed).
•	Challenges in dataset:
o	Missing values due to incomplete surveys.
o	Imbalanced distribution (fewer depressed vs. non-depressed samples).
o	Categorical and text-based responses requiring encoding.

Technologies & Libraries Used
•	Google Colab (for collaborative development)
•	Python 3.x
•	Libraries:
o	Pandas (data manipulation)
o	NumPy (numerical operations)
o	Scikit-learn (encoding, scaling, PCA, feature selection, SMOTE)
o	Matplotlib & Seaborn (visualization)

Steps in the Pipeline
(Data Cleaning → Encoding → Outlier Handling → Feature Scaling → Feature Engineering → Dimensionality Reduction → Feature Selection → Handling Imbalances → Final Prep)

Files in Repository
•	Untitled4.ipynb – Google Colab notebook with full preprocessing pipeline on the Depression Dataset.
•	README.md / .docx – Documentation of pipeline steps, dataset overview, and team contributions.

How to Run the Notebook
1.	Open the .ipynb file in Google Colab.
2.	Upload the Depression dataset (CSV/Excel file).
3.	Modify dataset path inside the notebook if needed.
4.	Run cells step by step in sequence.
5.	Final processed dataset will be available for machine learning models.

Team Contributions
•	Rashmi – Data Cleaning, Encoding Categorical Variables
•	Binara – Outlier Detection & Removal
•	Himaya – Feature Scaling / Normalization
•	Jenode – Feature Engineering (New Features, Polynomial Features)
•	Vihanga – Dimensionality Reduction
•	Thanush – Feature Selection
•	Team – Handling Imbalances, Final Preparation

Future Work
•	Apply supervised learning models (Logistic Regression, Random Forest, Neural Networks).
•	Evaluate model performance with accuracy, F1-score, and ROC-AUC.
•	Investigate explainable AI methods to identify key depression risk factors.
•	Deploy as a mental health screening support tool.

