# Heart Disease Prediction

Problem Context
About 655,000 Americans die from heart disease each year—that’s 1 in every 4 deaths.
One person dies every 36 seconds in the United States from cardiovascular disease
Coronary heart disease is the most common type of heart disease, killing 365,914 people in 2017
Heart disease costs the United States about $219 billion each year from 2014 to 2015.This includes the cost of health care services, medicines, and lost productivity due to death.
Common Causes of some sort of heart disease
Overweight/Obesity
Diabetes
High Blood Pressure
High Cholesterol
Smoking
Predictive models play a crucial role in the healthcare sector, providing a tool to identify high-risk patients, predict disease progression, and assist in the decision-making process for personalized treatment plans. In this notebook, we will focus on creating a predictive model for heart disease risk. The risk model can support clinicians in diagnosing potential heart diseases earlier, thereby increasing the chance of effective treatment and improving the overall patient care process.

Dataset
The dataset used for this analysis is taken from the UCI Machine Learning Repository. Specifically, we use the Cleveland Heart Disease dataset, which is one of the most widely used datasets for heart disease prediction. The dataset contains patient records and a number of predictors relating to their medical history, lab test results, and lifestyle.

Data Dictionary
The dataset comprises the following attributes:

age: Patient's age in years
sex: Patient's sex (1 = male, 0 = female)
cp: Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
trestbps: Resting blood pressure in mm Hg
chol: Serum cholesterol in mg/dl
fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
restecg: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
thalach: Maximum heart rate achieved
exang: Exercise induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: The slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)
ca: Number of major vessels (0-3) colored by fluoroscopy
thal: Thallium stress test result (3 = normal, 6 = fixed defect, 7 = reversible defect)
target: Heart disease diagnosis (0 = no disease, 1 = disease)

Through exploratory data analysis, data preprocessing, feature importance analysis, and machine learning models implementation, we will attempt to create a predictive model for heart disease diagnosis using Jupyter Notebooks.
