1. # Project Title
Developer Salary and Job Satisfaction Prediction Using Machine Learning

The 2025 Developer Survey is the definitive report on the state of software development. In its fifteenth year, Stack Overflow received over 49,000+ responses from 177 countries across 62 questions focused on 314 different technologies, including new focus on AI agent tools, LLMs and community platforms.


2. # Problem Statement
“Software developers’ salaries and job satisfaction vary based on factors such as experience, education, country, programming languages, remote work status, and company size. This project aims to build machine learning models to predict developer salary and job satisfaction based on these attributes.”


3. # Objectives
Predict developer salary
Predict job satisfaction score
Identify features most affecting salary
Identify factors influencing satisfaction
Compare performance of different ML models

4. # Dataset
Dataset Source:
Stack Overflow Developer Survey Dataset
Features  include:
Age
Country
Years of coding experience
Employment type
Education level
Programming languages
Remote/on-site work
Company size
Target Variables:
Salary
Job satisfaction

5. # Methodology
Data Collection
Download and load dataset
Data Preprocessing
Handle missing values
Remove outliers
Encode categorical features
Normalize numerical features
Exploratory Data Analysis

## Analyze:
Salary distribution
Satisfaction trends
Correlation between variables

## Model Building
For salary prediction (regression) we use stacking:
### Base model:
Gradiant boosting
XGBoost
Light gbm
### Final Model:
Ridge 

For job satisfaction:
Light gbm


7. # Evaluation Metrics
For salary prediction:
MAE
RMSE
R²
For satisfaction classification:
Accuracy
Precision
Recall
F1-score

8. #  Expected Outcomes 
“The system will predict developer salary with acceptable accuracy and then predict job satisfaction.”

9. # Tools & Technologies
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Optuna
Light gbm
Xgboost
Cat boost
Jupyter Notebook

10. # Project Workflow
You can present it like:
Dataset → Cleaning → EDA → Visiualization → Pipelines → Model Training → Update Data → 2nd Model Training → Evaluation → Prediction

12. Limitations
Include realistic constraints:
Dataset bias
Missing values
Salary differences across countries
Self-reported survey inaccuracies.



