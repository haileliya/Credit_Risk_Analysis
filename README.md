# Credit_Risk_Analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


##Overview of the analysis: Explain the purpose of this analysis.##

For this analysis, the data source that was used was LoanStats_2019Q1.csv file and Python to evaluate several machine learning models to predict risk. 

##Results: 

##RandomOverSampler Model
                  pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.62      0.68      0.02      0.65      0.42        87
   low_risk       1.00      0.68      0.62      0.81      0.65      0.42     17118

avg / total       0.99      0.68      0.62      0.80      0.65      0.42     17205

The balanced accuracy score was 0.65 (0.6497536370265621), the precision score is 0.99 and the recall score is 0.68.

##SMOTE
                  pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.63      0.66      0.02      0.64      0.41        87
   low_risk       1.00      0.66      0.63      0.79      0.64      0.42     17118

avg / total       0.99      0.66      0.63      0.79      0.64      0.42     17205

The balanced accuracy score was 0.64 (0.6443721269403855), the precision score is 0.99 and the recall score is 0.66.

##Cluster Ceentroids
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.59      0.44      0.01      0.51      0.26        87
   low_risk       1.00      0.44      0.59      0.61      0.51      0.25     17118

avg / total       0.99      0.44      0.59      0.60      0.51      0.25     17205

The balanced accuracy score was 0.93 (0.9316600714093861), the precision score is 0.99 and the recall score is 0.44.

##Smoteenn
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.71      0.56      0.02      0.63      0.41        87
   low_risk       1.00      0.56      0.71      0.72      0.63      0.40     17118

avg / total       0.99      0.56      0.71      0.72      0.63      0.40     17205

The balanced accuracy score was 0.51 (0.5117037520496674), the precision score is 0.99 and the recall score is 0.56.

##Balanced Random Forest Classifier
                  pre       rec       spe        f1       geo       iba       sup

  high_risk       0.03      0.70      0.87      0.06      0.78      0.60       101
   low_risk       1.00      0.87      0.70      0.93      0.78      0.62     17104

avg / total       0.99      0.87      0.70      0.93      0.78      0.62     17205

The balanced accuracy score was 0.79 (0.7885466545953005), the precision score is 0.99 and the recall score is 0.87.

##Easy Ensemble Classifer Model
               pre       rec       spe        f1       geo       iba       sup

  high_risk       0.09      0.92      0.94      0.16      0.93      0.87       101
   low_risk       1.00      0.94      0.92      0.97      0.93      0.87     17104

avg / total       0.99      0.94      0.92      0.97      0.93      0.87     17205

The balanced accuracy score was 0.93 (0.9316600714093861), the precision score is 0.99 and the recall score is 0.94.
