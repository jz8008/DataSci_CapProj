
This repository is the submission for the Capstone project for Udacity Data Scientist Nano Degree.

In this project, collected event log data from a music streaming company Sparkify was explored and some classifier models were used to predict the user churn, the results from different models were evaluated with F1 score. We use PySpark to work on this project. A small chunk (128 MB) data set from a big full data set (12 GB) was used to explore the data and train/test the machine learning model. A medium sized (230 MB) data and the analysis tool, selected models will be deployed to IBM Watson studio later.


This repository holds this readme file and one pyspark Python note book: 
README.md
Sparkify_final.ipynb

In the notebook, raw data will be read in and cleaned up. Data was explored and features and label are identified and preprocessed. Then the Logistic Regression model, Random Tree Classifier model and Gradient Boosted Tree model are trained, tested and validated with the feature/label data. The results are evaluated and the models were tuned with cross validation of the selected parameters. 
 
It should be noted that some data exploration codes (such as some feature analysis and ploting) are not included in this notebook because they will not be deployed to the IBM Waston studio.



