# Big-Data-project
Defaulter Classification

### Summary
Create various parametric and non-parametric models to predict default of a company

### In Detail
In this excercise I developed various models in order to classify companies into defaulters and non-defaulters.

The first set of models implemented have been parametric ones such as LDA, QDA, Logistic Regression and Linear Regression for classification. The overall performance of the models was mixed with LDA and Logistic regression taking the lead.

The second set of models was used were non-parametric models like a decision tree, random forest and a neural network. The performance of these models was exceptionaly higher than the first set, with Random Forest achieving the best results.

The model evaluation metrics have been the standard accuracy score, precision-recall and ROC-AUC curve. For 

### Methodology
After importing the data and making all necessary filtering we calculate the covariance matrix in order to understand more about the underlying structure of the features. Moreover, we explore further irregularities about the dataset and conclude that the underlying data is imbalanced. For that reason when we implement the parametric models we have to first use SMOTE in order to generate synthetic data and convert the dataset balanced.

After that we use train_test_split in order to split the data into 70% train and 30% test. 
From there we train each individual model and evaluate it on the test set.
