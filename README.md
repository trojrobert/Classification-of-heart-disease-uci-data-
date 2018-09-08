# Classification-of-heart-disease-uci-data-
Using some machine learning classification model to classify if a patient have heart disease or not 
[Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
## EXPLORATORY DATA ANALYSIS 

We will explore the dataset to understand the data and to see what we can deduce from it.

This database contains 14 attributes, The "target" column is our dependent variable 

### Discription of the data attribute 
1. **age:** age in years
2. **sex:** sex (1 = male; 0 = female)
3. cp: chest pain type -- Value 1: typical angina -- Value 2: atypical angina -- Value 3: non-anginal pain -- Value 4:    asymptomatic
4. trestbps: resting blood pressure (in mm Hg on admission to the hospital) trestbps
5. chol: serum cholestoral in mg/dl
6. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
7. restecg: resting electrocardiographic results -- Value 0: normal -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina (1 = yes; 0 = no)
10. oldpeak = ST depression induced by exercise relative to rest 
11. slope: the slope of the peak exercise ST segment -- Value 1: upsloping -- Value 2: flat -- Value 3: downsloping
12. ca: number of major vessels (0-3) colored by flourosopyca
13. thal: 3 = normal; 6 = fixed defect 
14. **target** - diagnosis of heart disease (angiographic disease status) -- Value 0: < 50% diameter narrowing -- Value 1: > 50% diameter narrowing (in any major vessel: attributes 

## Objective 
+ We want to see the distribution male and females with heart disease 
+ We want to see the distribution of people with heart disease with respect to their age
+ Use different machine learning model to predict the if a patient has heart disease or not

## Machine Learning model used 
+ Logistic regression 
+ KNN
+ Naive Bayes
+ SVC
+ Decision treee classification 
+ Random forest classification 



