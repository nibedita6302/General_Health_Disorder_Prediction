# General_Health_Disorder_Prediction

The aim of this project is to predict possible health problems that an individual might be having based on common factors like itching, skin rashes, sneezing, etc. 
Models used for training are Random Forest Classifier, Decision Tree, KNN and SVM. Hyper-parameter tuning for all model then provided the best result in KNN model. Among which KNN has been choosen as the final trained model. 
The data consists of 130 different symptoms classified into 42 different diseases. A comprehensive chart of the same is given below - 

<img src="https://github.com/nibedita6302/General_Health_Disorder_Prediction/assets/145376728/d09d0dd8-5c39-4e87-b737-35d6408e8d6f" alt="pieChart" height="400">

# **Decision Tree:**
* A decision tree is a flowchart-like structure where each internal node represents a "test" on an attribute, each branch represents the outcome of the test, and each leaf node represents a class label.
* Decision trees are intuitive and easy to interpret, making them useful for understanding the logic behind classification decisions.
* However, they can be prone to overfitting, especially with complex datasets.
# Support Vector Machine (SVM):
* SVM is a powerful supervised learning algorithm used for classification, regression, and outlier detection.
* SVM works by finding the optimal hyperplane that best separates the data points of different classes in a high-dimensional space.
* It is effective in high-dimensional spaces and is memory efficient since it only uses a subset of training points (support vectors) to define the decision boundary.
* SVM can handle non-linear decision boundaries using techniques like the kernel trick.\
# Random Forest:
* Random Forest is an ensemble learning method that combines multiple decision trees to create a more robust and accurate model.
* Unlike a single decision tree, which can overfit on the training data, Random Forest reduces overfitting by averaging the predictions of many trees trained on random subsets of the data.
* It introduces randomness both in the selection of data samples (bootstrap samples) and the features considered at each split, leading to diverse trees that collectively provide better generalization.
* Random Forest is known for its ability to handle high-dimensional data, large datasets, and maintain good performance without extensive hyperparameter tuning.

**In summary:**

* Decision trees are simple and interpretable but can overfit.
* SVM finds optimal hyperplanes in high-dimensional spaces and is effective for various types of data.
* Random Forest is a specific type of bagging classifier using decision trees, known for its robustness and ability to handle complex datasets.

## Confusion Matrix 
- Following is the confusion matrix created on test data -
<img src="https://github.com/nibedita6302/General_Health_Disorder_Prediction/assets/145376728/045b4567-43c6-4fb6-a0b8-29ff792f029d" alt="mtx" height="300" />

**Final Accuracy of the KNN model is about 98% with a loss of 5%**

> [!TIP]
> Check out disease predicition model on [Kaggle](https://www.kaggle.com/code/nibedita6302/disease-prediction)
