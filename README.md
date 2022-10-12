# Predicting heart disease using machine learning

The project on this notebook is designed to use Python-based machine learning and data science libraries to attempt to build a machine learning model that has the capacity to predict whether a person has heart disease or not based on their medical attributes.
## 1. Problem Definition
> With available clinical parameters about a patient, can we predict whether or not a patient has heart disease?
## 2. Data
### Creators
1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

Donor:

David W. Aha (aha '@' ics.uci.edu) (714) 856-8779
### Features
* age: age in years
* sex: sex (1 = male; 0 = female)
* cp: chest pain type
-- Value 0: typical angina
-- Value 1: atypical angina
-- Value 2: non-anginal pain
-- Value 3: asymptomatic
* trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* chol: serum cholestoral in mg/dl
* fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg: resting electrocardiographic results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
* thalach: maximum heart rate achieved
* exang: exercise induced angina (1 = yes; 0 = no)
* oldpeak = ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
-- Value 0: upsloping
-- Value 1: flat
-- Value 2: downsloping
* ca: number of major vessels (0-3) colored by flourosopy
* thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
* target: 0 = no disease, 1 = disease

For more information on datasets:
https://archive.ics.uci.edu/ml/datasets/heart+disease
https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci
## 3. Evaluation
> If we can reach 95% accuracy at predictiong whether or not a patient has heart disease during the proof of concept, we will pursue the project.