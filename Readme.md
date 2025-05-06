# Heart Disease Classification Model
This notebook looks into using various python based Machine learning and Data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

We are going to take the f0llowing approch
1. Problem defination
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Defination
in a statement,
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data
The original data came from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/heart+Disease

There is also a version of it available on Kaggle. 
https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset

## 3. Evaluation 
> If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

## 4. Features
This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.
The following are the features we'll use to predict our target variable (heart disease or no heart disease).

**Data Dictionary**

| Feature   | Description                                                                                       | Example Values                           |
|-----------|---------------------------------------------------------------------------------------------------|------------------------------------------|
| age       | Age in years                                                                                      | 29, 45, 60                                |
| sex       | 1 = male; 0 = female                                                                              | 0, 1                                     |
| cp        | Chest pain type                                                                                   | 0: Typical angina, 1: Atypical angina, 2: Non-anginal pain, 3: Asymptomatic |
| trestbps  | Resting blood pressure (in mm Hg on admission to the hospital)                                    | 120, 140, 150                             |
| chol      | Serum cholesterol in mg/dl                                                                        | 180, 220, 250                             |
| fbs       | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)                                             | 0, 1                                     |
| restecg   | Resting electrocardiographic results                                                              | 0: Normal, 1: ST-T Wave abnormality, 2: Left ventricular hypertrophy |
| thalach   | Maximum heart rate achieved                                                                       | 160, 180, 190                             |
| exang     | Exercise induced angina (1 = yes; 0 = no)                                                         | 0, 1                                     |
| oldpeak   | ST depression induced by exercise relative to rest                                                | 0.5, 1.0, 2.0                             |
| slope     | The slope of the peak exercise ST segment                                                         | 0: Upsloping, 1: Flatsloping, 2: Downsloping |
| ca        | Number of major vessels (0-3) colored by fluoroscopy                                              | 0, 1, 2, 3                                |
| thal      | Thalium stress result                                                                             | 1: Normal, 3: Normal, 6: Fixed defect, 7: Reversible defect |
| target    | Have disease or not (1 = yes; 0 = no)                                                              | 0, 1                                     |
