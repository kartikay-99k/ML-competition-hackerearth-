# [ML competition(hackerearth)](https://www.hackerearth.com/challenges/competitive/airplane-accident-severity-hackerearth-machine-learning-challenge/) 

-------------------------------------------------------------------------------------------------------------------------------

# Observation / Experiment and approach of each notebooks

## Notebook1  -:  

### Approach
1. Selecting K best features using  sklearn.feature_selection import SelectKBest.
2. Standardizing selected features.
3. Applying PCA.
4. Using different classifiers.
5. Lastly using stackingClassifier.

### Observation/Experiment
1. Using PCA was not good approach for this problem, since accuracy went down by 2%-10% for most of the classifier.
2. Scaling gave the best results.
3. According to experiments ,selecting all feature came out be a better option, since accuracy was the highest for most of the calssifiers.
4. For hyperparameter tuning ,I used RandomsearchCV. 
5. Use of Stackingclassifier gave the best result.


## Notebook2  -: 

### Approach

Almost Same as Notebook1 Used only for Hyperparametre tuning


## Notebook3  -:

### Approach/experiments

1. Data preprocessing and Visualizations.
2. Used LinearDiscriminantAnalysis + PCA
3. PCA X 2 (PCA followed by another PCA).

# Learning Experience

This competition helped me to learn following.
1. Different Classifiers (RidgeClassifier, RidgeClassifierCV, LogisticRegression, LogisticRegressionCV, SGDClassifier, Perceptron, SVC, KNeighborsClassifier , GaussianNB, DecisionTreeClassifier, GradientBoostingClassifier, BaggingClassifier, RandomForestClassifier, ExtraTreesClassifier, AdaBoostClassifier, OneVsRestClassifier ,OneVsOneClassifier ,OutputCodeClassifier , MLPClassifier ,LinearDiscriminantAnalysis )
2. Hyperparametre tuning using RandomizedSearchCV ,GridsearchCV.
3. Feature secletion technique.
4. Boosting technique such as Gradientboosting, XGboost, Adaboost.

