# yelp-deceptive-review-detection

### Dataset

The yelp dataset that I have used in this project have 2 classes, the true reviews class and the spam reviews class. This dataset is available on request on the mail: srayana@cs.stonybrook.edu


### Model Training

I have used 5 machine learning algorithms which are : 1) Decision Tree 2) Bagging Classifier 3) Random Foreset 4) KNN 5) AdaBoost
and finally I have ensembled all these 5 trained algorithms in hard majority voting classifier. 

### SMOTE

This dataset is imbalanced and the minority class is the spam reviews class. Therefore to handle this imbalaned dataset, I have used the oversampling technique called as SMOTE which generates the artificial samples of minority class.
