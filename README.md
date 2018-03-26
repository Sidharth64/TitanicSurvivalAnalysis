# TitanicSurvivalAnalysis
The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships. In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

To start with this a kaggle question (https://www.kaggle.com/c/titanic) . We start by importing the dataset then by reading it and pre - processing it.Some good insightful visualisations alongwith Feature engineering followed next.Feature storing the passenger name was processed and exploited to create a new feature containing the designation of all passengers which had significant coorelation with the target variable. We then use mean and mode to impute missing values in the data . Then we create our base model with decision tree alongwith with validation to address the issue of overfitting by limiting the depth of the tree. We also apply XGboost to this model in order to improve the performance. We check the accuracy and quality of this model by confusion matrix.

Python As usual, we will first download our datasets locally, and then we will load them into data frames in both, python. Source of dataset : https://archive.ics.uci.edu/ml/datasets/Housing In python, we use pd.read_csv to read CSV files into pandas data.frame variables. Libraries used : 

1)library(pandas) #to read .csv file .

2)library(numpy) #for preprocessing and and data manipulation.

3)library(sklearn.preprocessing) #for LabelEncoder(). 

4)library(sklearn.metrics) #for evaluating the performance. 

5)library(sklearn.model_selection) #for train_test_split and fine-tuning the model parameters.

6)library(matplotlib) #for data visualisation.

7)library(xgboost) #for applying XGboost. 

8) library(sklearn.Tree) #for Decision Tree .

