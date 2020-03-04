# WorkingWithUnlabeledColumns
Data Science Project Showcase

Data:
This dataset was sent to me by a prospective employer with instructions on the steps to carry out the modeling process from start to end.  This included data cleaning and EDA, modeling and predictions and explanation of model performance measured by AUC.

Process:
Due to the columns being unlabeled, it was hard to understand what the meaning behind the data was. Out of the 100 columns (40,000 rows), 96 columns were of type float, with values ranging from -4 to 4, and -1000s to 1000s. The remaining columns were categorical columns with values such as vehicle types, day of the week, continent and month.

To start off, i decided to get a running baseline to see how easy or hard the problem was.

With no EDA and feature selection, the basic model returned a good 86%.

I tried running a few other models after cleaning and tidying the data and they were returning a good ROC AUC score of 92% and 93%.

My final model was Light GBM which yielded a 96% accuracy rate. This meant that it would be 96% accurate on determining wether or not it classified my target as 0 or 1.

My problem was a classification problem, to determine wether target would fall in 0 or 1 based on 100 features.

Conslusion:
Due to the uncertainty of the problem, it is hard to say what is being predicted, but to name a few things which could be associated with the dataset:

1-insurance fraud
2-vehicle sales
3-insurance claims
4-accident statistics


