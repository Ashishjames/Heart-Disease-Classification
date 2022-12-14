# Heart-Disease-Classification
## Problem Statement
Given clinical parameters of patient, can we predict whether or not they have heart disease? 

## Datasets Used

The original data came from the Cleveland data from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/heart+disease

There is also a version of it available on Kaggle: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

## Frameworks used
* Numpy 
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn

## Heart Disease Data Dictionary
A data dictionary describes the data you're dealing with.In particular, the Cleveland database is the only one that has been used by ML researchers to this date.The "target" field refers to the presence of heart disease in the patient.The following are the features we'll use to predict our target variable (heart disease or no heart disease):

* age - age in years
* sex - (1 = male; 0 = female)
* cp - chest pain type \
        0: Typical angina: chest pain related decrease blood supply to the heart \
        1: Atypical angina: chest pain not related to heart \
        2: Non-anginal pain: typically esophageal spasms (non heart related) \
        3: Asymptomatic: chest pain not showing signs of disease
* trestbps - resting blood pressure (in mm Hg on admission to the hospital) anything above 130-140 is typically cause for concern
* chol - serum cholesterol in mg/dl
* serum = LDL + HDL + .2 * triglycerides above 200 is cause for concern
* fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false) '>126' mg/dL signals diabetes
* restecg - resting electrocardiographic results \
         0: Nothing to note \
         1: ST-T Wave abnormality can range from mild symptoms to severe problems signals non-normal heart beat \
         2: Possible or definite left ventricular hypertrophy Enlarged heart's main pumping chamber
* thalach - maximum heart rate achieved
* exang - exercise induced angina (1 = yes; 0 = no)
* oldpeak - ST depression induced by exercise relative to rest looks at stress of heart during exercise unhealthy heart will stress more
* slope - the slope of the peak exercise ST segment \
         0: Upsloping: better heart rate with exercise (uncommon) \ 
         1: Flat Sloping: minimal change (typical healthy heart) \
         2: Downsloping: signs of unhealthy heart
* ca - number of major vessels (0-3) colored by fluoroscopy colored vessel means the doctor can see the blood passing through. The more blood movement the better (no clots)
* thal - thallium stress result \
          1,3: normal \
          6: fixed defect: used to be defect but ok now\
          7: reversible defect: no proper blood movement when exercising
* target - have disease or not (1=yes, 0=no) (= the predicted attribute)

## MODEL VISUALIZATIONS




![1](https://user-images.githubusercontent.com/101040910/182018121-f2f6c19f-76b4-4a01-b727-36aad0334b5a.JPG)

![2](https://user-images.githubusercontent.com/101040910/182018124-f5a81fd0-07c3-49f4-aed0-024ed06386ef.JPG)

![3](https://user-images.githubusercontent.com/101040910/182018130-b378df1f-6dd2-406e-b833-35ec3f2e886f.JPG)

![4](https://user-images.githubusercontent.com/101040910/182018133-3d50be9c-f71f-4321-b242-ef614bbde1c8.JPG)

![5](https://user-images.githubusercontent.com/101040910/182018140-130f3a9b-e0f4-4aa8-958f-1428a43f454f.JPG)

![6](https://user-images.githubusercontent.com/101040910/182018141-ede219c7-1426-4845-a748-2eed4e930884.JPG)

![7](https://user-images.githubusercontent.com/101040910/182018144-39f84e9b-8a7e-40da-b68b-c9c53a084113.JPG)
