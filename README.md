# Image Classification using SVM
Support Vector Machine is used for binary classification. It can be used for multiclass classification by using One vs One technique
or One vs Rest technique.

One vs One technique has been used in this case.

## One vs One
If we have n classes then we train nC2 classifiers and each classifier learns its own set of weights and parameters for every data pair.
Prediction is made by majority vote from nC2 classifiers.

Scikit Learn uses One vs One technique for multiclass classification using SVM

### Accuracy
* Implementing One vs One technique on a SVM Classifier made from scratch
  - Accuracy - 60.02%



* Using scikit learn
  - Accuracy - 63.11%
