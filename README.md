Predicting heart disease using machine learning
this notebook looks into using various python based machine learning and datascience libraries in an attempt to build a machine learning model capable of predicting whether or no not someoe has heart disease based on their medical attributes.

we are going to take the following approach:

problem definition
Data
Evaluation
Features
Modeling
Experimentation
1. Problem Definition
In a statement,

Given clinical parameters about a patient can we predict whether or not they have heart disease?

2. Data
the original data came from the cleaveland data from the UCI Machine learing Repository

There is also a version of it available on kaggle. https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

3. Evaluation
If we can reach 95% accuracy at predicting whether or not a patient has hear disease duting the proof of concept, we'll pursue the project.

4. Features
this is where youl get diffeent inforamation about each of the features in your data.

Create data dictionary

age
sex, (1=male; 0=female)
chest pain type (4 values)
resting blood pressure
serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect
The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.
