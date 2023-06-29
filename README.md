# Ensemble Methods

Using ensemble learning techniques to classify handwritten digits.

Topics covered include:
- simple voting classifiers using hard and soft voting strategies
- bagging and pasting ensembles
- boosting and early stopping
- popular ensemble-based learning algorithms including `RandomForests` and `AdaBoost`

Submitted as coursework in my second year at the University of Bath.

See the [notebook](./Practical3.ipynb) for details.

## Summary of Classifiers and Their Results

### Bagging Classifier & Out of Bag Score
```
Out of Bag score: 0.9502598366740905
Accuracy: 0.9555555555555556
```

### Random Forest Classifier
```
Accuracy: 0.9333333333333333
```

### Voting Classifier (hard)
Using ensemble made from logistic regression, random forest, and support vector machines.
```
Accuracy: 0.98
```

### Soft Voting Classifier 
Using ensemble made from logistic regression, random forest, and support vector machines.
```
Accuracy: 0.9822222222222222
```

### AdaBoost
```
Accuracy: 0.8177777777777778
```