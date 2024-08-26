In this work, logistic regression model is deployed to predict heart disease probability. The workflow covers scnearios of dataset with and without handling the outliers. It is rather interesting observation that some of the dataset may not necessarily need extensive Exploratory Data Analysis and Feature engineering todevelop accurate prediction model. In this particular example, Accuracy of logistic regression classifier on test set is 0.85 for the case where handling outliers and dataset balancing is bypassed and 0.90 where full outliers are removed and dataset is balanced.
Small difference is observed between model accuracy results and in fact the ROC (Receiver operating characteristic) looks better for the dataset where outliers were not removed.
The outcome of this work rather tells me that in some cases outliers does not necessarily impact negatively on model prediction accuracy and you would want to keep them in the dataset since they may form crucial part of the data, which is used for model training.
