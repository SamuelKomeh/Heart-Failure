# Heart-Failure
Goal: To develop a machine, ensembled method and artificial intelligence or deep learning algorithm to detect and predict the presence or absence (accuracy) of cardiovascular disease (heart failure) based on the other variables¶
Cardiovascular disease (Heart Failure)
With an estimated 840,768 deaths in 2016, cardiovascular disease is the top cause of mortality in the United States. However, almost 200,000 fatalities each year may be prevented with modest lifestyle changes and screening. Using only standard health information, we will examine different machine learning approaches for detecting the presence of cardiovascular disease. We use both traditional machine learning and state-of-the-art deep learning techniques.

The machine learning techniques include a Random Forest classifier, Logistic Regression, Linear support vector machine (SVM), adaboost classifier, bagging, decision tree classifier. For our deep learning technique, we also use a multilayer preceptron neural network for this cardiovascular disease detection

In addition to utilising these methods to diagnose cardiovascular disease, we will explore which data features are most indicative for the disease. With nearly 70,000 patients, our dataset contains standard health information as well as information on the presence or absence of cardiovascular disease. Our goal here is not only to develop a classifier to detect the existence of cardiovascular disease, but also to discover which aspects and types of data (demographic, examination, and social history) are most beneficial for disease prediction. With the findings of this study, physicians may be able to modify their existing case history procedures in order to gather more valuable data from their patients.

Dataset
The cardiovascular disease dataset is an open-source dataset produced by Svetlana Ulianova in canada and uploaded on Kaggle in the year 2018. The data set consists of 70,000 patient records (34,979 with cardiovascular disease and 35,021 without) and includes 11 characteristics (4 demographic, 4 examination, and 3 social history and also our target variable which is cardio.

The age (age) of the patient which is demographic ( int)(days)
Weight (weight) of the patient which is demographic (float) (kg)
Height (height) of the patient which is demographic (int)(cm)
The gender (gender) of the person which is demographic (categorical code)(Binary) which is 1 or 2, where 1 is women and 2 is men
Systolic blood pressure (api_hi) is the highest level of blood pressure, mainly the medical examination (int)
Diastolic blood pressure (api_lo) is the lowest level of blood pressure mainly the medical examination (int)
Cholesterol (cholesterol) is a kind of fat mainly the medical examination where 1: normal, 2: above normal, 3: well above normal, which is a categorical code (int)
Glucose (gluc) is a kind of sugamainly ther mainly the medical examination where 1: normal, 2: above normal, 3: well above normal, which is a categorical code (int)
Smoking (smoke) which is the smoking history of the patient (binary)
Alcohol (alco) intake which is the alcohol intake of the patient which is the social history (binary)
Physical activity (active) which is the activity of the patient. It describes whether the patient is or active or not, It also refers to the social history of the patients. (Binary)
Cardio which is the presence or absence of the diseases (Binary)
Some features are numerical, while others are assigned categorical codes, and others have binary values. Although the classes are balanced, more female patients were seen than male patients. Furthermore, the continuous-valued features are almost normally distributed; nevertheless, the some of the categorical values are skewed, when will address all in our analysis
