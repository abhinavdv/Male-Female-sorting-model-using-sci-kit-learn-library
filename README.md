# Male-Female-sorting-model-using-sci-kit-learn-library
A male-female sorting model which uses sci-kit learn library. The three different classifiers used in respective order are Descision tree classifier, Random Forest Classifier and the K Neighbors classifier.

The model takes as input three X and Y which is the data. X is an array of arrays whaich contains the height, weight and shoe size of a person in respective order. Y contains an array of strings which has the data wether the corresponding values in X are that of a Male or of a Female. In this model, only two genders are taken into account.

The three classifiers used here are the Descision tree classifier, Random Forest Classifier and the K Neighbors classifier.

1) Decision tree
  Definition: Given a data of attributes together with its classes, a decision tree produces a sequence of rules that can be used to classify the data.
  Advantages: Decision Tree is simple to understand and visualise, requires little data preparation, and can handle both numerical and categorical data.
  Disadvantages: Decision tree can create complex trees that do not generalise well, and decision trees can be unstable because small variations in the data might result in a completely different tree being generated.
  
2) Random Forest Classifier
  Definition: Random forest classifier is a meta-estimator that fits a number of decision trees on various sub-samples of datasets and uses average to improve the predictive accuracy of the model and controls over-fitting. The sub-sample size is always the same as the original input sample size but the samples are drawn with replacement.
  Advantages: Reduction in over-fitting and random forest classifier is more accurate than decision trees in most cases.
  Disadvantages: Slow real time prediction, difficult to implement, and complex algorithm.
  
3) K Neighbors classifier(K-neraest neighbors)
  Definition: Neighbours based classification is a type of lazy learning as it does not attempt to construct a general internal model, but simply stores instances of the training data. Classification is computed from a simple majority vote of the k nearest neighbours of each point.
  Advantages: This algorithm is simple to implement, robust to noisy training data, and effective if training data is large.
  Disadvantages: Need to determine the value of K and the computation cost is high as it needs to computer the distance of each instance to all the training samples.

Source for definitions:https://www.analyticsindiamag.com/7-types-classification-algorithms/
