﻿# Titanic - Machine learning from Disaster 

![image](https://github.com/HaColab2k/Data-analyst/assets/127838132/b11be7b6-9a20-4b88-97dd-dee9a4051ace)

This is a Kaggle competition for those who are passion about data analyst, data science, etc. The topic of this challenge is about [the sinking of the Titanic](https://en.wikipedia.org/wiki/Sinking_of_the_Titanic) is one of the most infamous shipwrecks in history.
## Table of contents
- [Overview](#overview)
- [Dataset description](#Dataset-description-and-features-classification)
- [Data preprocessing](#Data-preprocessing)
- [Features classification](#Features-classification)
- [Reference](#Reference)
## Overview
In this competition, I used [Kaggle's API](https://www.kaggle.com/docs/api) to download datasets which are unzipped by using Zipfile and Os modules then I used Numpy, Pandas for numerical computations, data manipulation, and analysis. Finally, I used binary classification technique of machine learning to create a model that predicts which passengers survived the Titanic shipwreck.
## Dataset description
The [data](https://github.com/HaColab2k/Data-analyst/tree/main/Projects/.kaggle) has been split into two groups:
- training set (`train.csv`)
- test set (`test.csv`)
- example(gender_submission.csv)
I used training set to train the machine learning models and test set to estimate the models. In addition, gender_submission.csv is a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

`Data dictionary`

![image](https://github.com/HaColab2k/Data-analyst/assets/127838132/3eddd888-45cf-4db1-8f2d-59f4e3af6407)

## Data preparing
- Download datasets
- Unzip datasets
## Data preprocessing
- Load datasets
- Overview
- Data cleaning
## Features classification
- `Categorical`: Survived, Sex, Embarked, Pclass(ordinal), SibSp, Parch
- `Numerical: Age(continuous), Fare(discrete)
- Mix types of data: Ticket, Cabin
- Contain Error/Typo: Name
- Blank or Null: Cabin > Age > Embarked
- Various Data Type: String, Int, Float

## Reference
Will Cukierski. (2012). Titanic - Machine Learning from Disaster. Kaggle. https://kaggle.com/competitions/titanic
