# kaggle_titanic
This notebook demonstrates basic data exploration, data processing, feature engineering, and supervised machine learning techniques.
The goal of this repository is to record where I started as a beginner in the the field of data science and Kaggle's competitions.

#### File Description 
* Datasets: *train.csv* &  *test.csv*
* Notebook: *Titanic.ipynb*
* Decision Tree image: *tree.png*
* Result: *titanic_sub_eclf4.csv*

## Kaggle Competition | Titanic Machine Learning from Disaster

> The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

> One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

> In this contest, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.
This Kaggle Getting Started Competition provides an ideal starting place for people who may not have a lot of experience in data science and machine learning.

From the competition [homepage](https://www.kaggle.com/c/titanic).

**In this notebook you can see how I analyze the problem of the Titanic disaster in Python:**

### Data Exploration 
* Importing Data with Pandas
* Exploring Data through statistics (mean, mode, standard deviation, correlation, types of variables) 

### Data Processing 
* Impute missing values
* Remove outliers 
* Add potentially-useful features based on other features 
* Label Encoder

### Feature Engineering 
Supervised Machine learning Techniques:
* K-Neighbors Classifier
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting 
* (Voting Classifier)

Tuning Parameters:
* GridSearchCV

## Insights
Through the decision tree and the feature importances, I observed that for female, their class (economic status) is the most critical feature of their survival; for male, it's age. Additionally, for both genders, a smaller family size (<3.5 members) has a higher chance to survive. 

## Result 
Based on this analysis, I got a score of 0.78 and ranked top 51%. 
My [profile](https://www.kaggle.com/chingchen) on Kaggle. 

