# ML competition(hackerearth) 

---------------------------------------------------------------------------------------------------------------------------------

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
