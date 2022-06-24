# Credit_Risk_Analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


##Overview of the analysis: Explain the purpose of this analysis.##

For this analysis, the data source that was used was LoanStats_2019Q1.csv file and Python to evaluate several machine learning models to predict risk. 

##Results: 

##RandomOverSampler Model
![image](https://user-images.githubusercontent.com/96396696/175616400-13df0a06-577c-4589-ab1e-bb9d00cb1fc2.png)

The balanced accuracy score was 0.65 (0.6497536370265621), the precision score is 0.99 and the recall score is 0.68.

##SMOTE
![image](https://user-images.githubusercontent.com/96396696/175616290-836259fc-6c0e-4e33-b397-e25588bce7a8.png)

The balanced accuracy score was 0.64 (0.6443721269403855), the precision score is 0.99 and the recall score is 0.66.

##Cluster Ceentroids
![image](https://user-images.githubusercontent.com/96396696/175616188-7fd15e3b-ee18-4dc3-b37c-b60c1acba0a3.png)

The balanced accuracy score was 0.93 (0.9316600714093861), the precision score is 0.99 and the recall score is 0.44.

##Smoteenn
![image](https://user-images.githubusercontent.com/96396696/175616104-a8965472-365e-4051-9d59-2e1a5197fa91.png)

The balanced accuracy score was 0.51 (0.5117037520496674), the precision score is 0.99 and the recall score is 0.56.

##Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/96396696/175615994-32e33806-0dc8-499f-badf-289e2d827a76.png)

The balanced accuracy score was 0.79 (0.7885466545953005), the precision score is 0.99 and the recall score is 0.87.

##Easy Ensemble Classifer Model
![image](https://user-images.githubusercontent.com/96396696/175615839-eb794917-1e9a-41a9-8e1d-be55311bf396.png)

The balanced accuracy score was 0.93 (0.9316600714093861), the precision score is 0.99 and the recall score is 0.94.
