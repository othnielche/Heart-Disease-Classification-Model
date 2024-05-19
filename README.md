# Heart-Disease-Classification-Model

## Predicting heart disease using machine learning

This notebook looks into using various Python-Based machine learning and data science libaries in an attempt to build  machine learning model capable of predicting wether or not someone has heart disease based on their medical attributes.

We're going to take the following approach:
1. Problem definition
2. Data 
3. Evaluation 
4. Features
5. Modelling
6. Experimentation 


## 1. Problem definition

In a statement,
> Given clinical paraemters about a patient can we predict wether or not they have heart disease?

## 2. Data 
The original data came from Cleaveland data from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/dataset/45/heart+disease

There is also a version of it available on Kaggle.
https://www.kaggle.com/datasets/ketangangal/heart-disease-dataset-uci/

## 3. Evaluation 

> If we can reach 95% accuracy at predicting whether or not a patient has heart disease duting the proof of concept, we will persue the project.

## 4. Features

**Data dictionary**

1. age
2. sex (male : 1, female : 0)

3. chest pain type(cp)
   - Value 1: typical angina
   - Value 2: atypical angina
   - Value 3: non-anginal pain
   - Value 4: asymptomatic

4. resting blood pressure (in mm Hg on admission to the hospital)

5. cholserum cholestoral in mg/dl

6. fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

7. resting electrocardiographic results
   - Value 0: normal
   - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
   - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

8. thalach: maximum heart rate achieved

9. exercise induced angina (1 = yes; 0 = no)

Angina is chest pain or discomfort caused when your heart muscle doesn't get enough oxygen-rich blood.
It may feel like pressure or squeezing in your chest.

10. oldpeak = ST depression induced by exercise relative to rest

11. slope: the slope of the peak exercise ST segment
    - Value 1: upsloping
    - Value 2: flat
    - Value 3: downsloping

12. vessels colored by flourosopy : number of major vessels (0-3) colored by flourosopy

13. A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

14. Target : 0 No Heart disease, 1 Heart disease