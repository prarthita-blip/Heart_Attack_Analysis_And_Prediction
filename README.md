# Heart_Attack_Analysis_And_Prediction

Install

The project requires python and following python libraries installed:
1.	numpy
2.	pandas
3.	matplotlib
4.	seaborn
5.	scikit-learn

The project has been executed using a jupyter notebook.

Data

The dataset used in this project is the “Heart attack Analysis and Prediction dataset” available at Kaggle.

The data has the following columns:
1.age: Age of the patient
2.sex: Sex of the patient
3.cp: Chest pain type, 0 = Typical Angina, 1 = Atypical Angina, 2 = Non-anginal Pain, 3 = Asymptomatic
4.trtbps: Resting blood pressure (in mm Hg)
5.chol: Cholesterol in mg/dl fetched via BMI sensor
6.fbs: (fasting blood sugar > 120 mg/dl), 1 = True, 0 = False
7.restecg: Resting electrocardiographic results, 0 = Normal, 1 = ST-T wave normality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria
8.thalach: Maximum heart rate achieved
9.oldpeak: Previous peak
10.slp: Slope
11.ca: Number of major vessels
12.thall: Thallium Stress Test result, (0-3)
13.exng: Exercise induced angina, 1 = Yes, 0 = No
14.target: 0 = less chance of heart attack, 1 = more chance of heart attack

Code

The code analyses the entire dataset, it tries to find out the relation between various columns and how each column is affecting the chances of a person being prone to heart attack. Libraries such as numpy, pandas, matplotib and seaborn have been used to pre-process, visualise and analyse the dataset.
The model uses information like age, sex, cholesterol, blood sugar and some components of ECG test and Thallium test to predict if the person is prone to heart attack or not. Algorithms like Logistic Regression, DecisionTree, RandomForest, KNearestNeighbours and SupportVectorClassifier have been used for predictive analysis and the model with highest accuracy has been chosen as the final model.

Result

SupportVectorClassifier turned out to be the best fit model with an accuracy of 93.44%. 
There is great scope for this project in the medical field. It can automate the analysing of medical test results, without human intervention.
There is also scope for improvement as the size of the dataset was very small (303 rows). With a larger dataset the accuracy of this model can be increased further.
