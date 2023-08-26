# Titanic - Machine learning from Disaster 

![image](https://github.com/HaColab2k/Data-analyst/assets/127838132/b11be7b6-9a20-4b88-97dd-dee9a4051ace)

This is a Kaggle competition for those who are passion about data analyst, data science, etc. The topic of this challenge is about [the sinking of the Titanic](https://en.wikipedia.org/wiki/Sinking_of_the_Titanic) is one of the most infamous shipwrecks in history.
## Table of contents
- [Overview](#overview)
- [Dataset description and features classification](#Dataset-description-and-features-classification)
- [Features classification](#Features-classification)
## Overview
In this compitition, I binary classification technique of machine learning to create a model that predicts which passengers survived the Titanic shipwreck. I used Kaggle's API to download and unzip datasets by using Zipfile and Os modules then using Numpy, Pandas for numerical computations, data manipulation and analysis.
## Dataset description
The data has been split into two groups:
-training set (train.csv)
-test set (test.csv)
-example(gender_submission.csv)
I used training set to train the machine learning models and test set to estimate the models. In addition, gender_submission.csv is a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.
### Data dictionary
![image](https://github.com/HaColab2k/Data-analyst/assets/127838132/3eddd888-45cf-4db1-8f2d-59f4e3af6407)
### Variable Notes
pclass: A proxy for socio-economic status (SES)
  1st = Upper
  2nd = Middle
  3rd = Lower
age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5
sibsp: The dataset defines family relations in this way...
  Sibling = brother, sister, stepbrother, stepsister
  Spouse = husband, wife (mistresses and fiancés were ignored)
parch: The dataset defines family relations in this way...
  Parent = mother, father
  Child = daughter, son, stepdaughter, stepson
  Some children travelled only with a nanny, therefore parch=0 for them.

## Features classification
Categorical: Survived, Sex, Embarked, Pclass(ordinal), SibSp, Parch
Numerical: Age(continuous), Fare(discrete)
Mix types of data: Ticket, Cabin
Contain Error/Typo: Name
Blank or Null: Cabin > Age > Embarked
Various Data Type: String, Int, Float
