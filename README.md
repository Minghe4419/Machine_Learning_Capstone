# Machine_Learning_Capstone
A capstone project from NYU Fundamental of Machine Learning
This is a supervised learning because data are labeled with `genre`.
## Clean Data
Replacing na with mean value and normalizing variables(`popularity`, `duration_ms`, `tempo`). Split data into train and test sets.
## Dimension Reduction
Using LinearDiscriminantAnalysis with `n_components=9`.
## Clustering
Comparing results of kmean and DBSCAN. Choose to use result from kmeans because DBSCAN is always underfitting.
## Checking Performance
Fitting training set into SVM, Random Forest, and Neural Network to check AUC and plot ROC curve.
