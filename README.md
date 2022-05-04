# Income-level
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting income level based on the individual's personal information. 


# Features
This is where we'll get different information about each of the features in the data.

create data dictionary

age: age in years (int)
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
fnlwgt: final weight (the number of people the census believes the entry represents)
education: Highest level of education.
Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
education-num: Highest level of education in numerical form.
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
sex: Female, Male.
0 = male
1 = female
capital-gain: capital gains for an individual.
capital-loss: capital loss for an indivdual.
hours-per-week: Hours an indivudal works per week.
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
Income class:
0 = <=50K
1 = >50K

# We're going to take the following approach:

Problem definition
Data
Evaluation
Features
Modelling
Experimentation
1. Problem Defintion
In a statement,

Given an individual's personal information, can we predict their income level?

2. Data
The original data came from the 1994 Census database. The dataset can be found at the UCI Machine Learning Respitory. https://archive.ics.uci.edu/ml/datasets/Adult

There is also a version of it available on Kaggle https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

3. Evaluation
If we can reach 85% accuracy at predicting income level, we'll pursue the project.

