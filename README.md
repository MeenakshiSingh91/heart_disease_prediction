Project Overview
This project predicts whether a patient has Diabetes using Machine Learning models implemented with PySpark MLlib.
It covers the full ML pipeline from data preprocessing to model evaluation.

Dataset Information
The dataset contains the following features:
•	Pregnancies 
•	Glucose 
•	BloodPressure 
•	SkinThickness 
•	Insulin 
•	BMI 
•	DiabetesPedigreeFunction 
•	Age 
•	Outcome (Target Variable) 
Total Records: 768
Target: Binary Classification (0 = No Diabetes, 1 = Diabetes)

Tech Stack
•	🐍 Python 
•	⚡ PySpark (MLlib) 
•	📊 Pandas, NumPy 
•	📉 Matplotlib, Seaborn 

Project Workflow
1.	Data Loading 
o	Loaded dataset using PySpark DataFrame 
2.	Data Exploration 
o	Checked schema, summary statistics 
o	Analyzed class distribution 
3.	Data Cleaning 
o	Handled zero values by replacing with mean 
o	Ensured data consistency 
4.	Feature Engineering 
o	Used VectorAssembler to combine features 
5.	Model Building 
o	Logistic Regression 
o	Decision Tree 
o	Random Forest 
o	Gradient Boosted Trees 
6.	Model Evaluation 
o	Compared models using accuracy 

Model Performance
Model	Accuracy
 Logistic Regression	83.83%
 Random Forest	76.36%
 Decision Tree	72.12%
 GBT Classifier	70.90%
 Best Model: Logistic Regression
 
Visualizations
•	Correlation Heatmap 
•	Feature Distribution Plots 
•	Feature Importance Graphs 

How to Run
 Install Dependencies
  pip install pyspark

