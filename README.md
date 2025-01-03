Heart Disease Exploratory Data Analysis (EDA)
Overview
This project explores a dataset on heart disease, focusing on identifying patterns and relationships between various attributes and the presence of heart disease. Through visualizations and statistical analysis, we aim to gain insights into key factors affecting heart health.

Features
Data Cleaning and Preprocessing: Ensures a clean dataset for analysis.
Univariate and Bivariate Analysis: Distributions and relationships between variables are analyzed.
Visualizations:
Distribution plots for numerical variables.
Pie charts for categorical variables.
Violin plots to observe distributions across different groups.
Correlation heatmaps and joint plots.
Pairplots for an overview of variable interactions.
Insights:
Analysis of age, cholesterol levels, and blood pressure as risk factors.
Investigation of categorical variables like chest pain type and ECG results.
Dataset
The dataset (heart.csv) contains the following features:

Age: Age of the patient.
Sex: Gender (M/F).
ChestPainType: Type of chest pain (e.g., ATA, NAP, ASY).
RestingBP: Resting blood pressure.
Cholesterol: Serum cholesterol levels.
FastingBS: Fasting blood sugar (binary).
RestingECG: Resting electrocardiogram results.
MaxHR: Maximum heart rate achieved.
ExerciseAngina: Exercise-induced angina (Y/N).
Oldpeak: ST depression induced by exercise relative to rest.
ST_Slope: The slope of the peak exercise ST segment.
HeartDisease: Diagnosis of heart disease (binary).
Dependencies
Python (3.x)
Pandas
NumPy
Matplotlib
Seaborn
Getting Started
Clone this repository:
bash
Copy code
git clone https://github.com/your_username/heart-disease-eda.git
cd heart-disease-eda
Install required packages:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook or Python script to explore the data.
Results
Visual insights from the EDA suggest significant correlations between certain features (e.g., age, cholesterol, max heart rate) and the presence of heart disease.
Data visualizations highlight patterns and risk factors.
Contribution
Feel free to open issues or contribute by submitting a pull request.

License
This project is licensed under the MIT License.