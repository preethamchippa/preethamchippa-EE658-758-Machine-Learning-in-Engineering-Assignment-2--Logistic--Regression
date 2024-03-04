# preethamchippa-EE658-758-Machine-Learning-in-Engineering-Assignment-2--Logistic--Regression

# Logistic Regression with Non-linear Decision Boundary
- This project explores various approaches to creating predictive models using logistic regression for a dataset with two classes that are not easily separable by a linear decision boundary. The project is divided into four parts.

# Part A: Logistic Regression with Scikit-learn
- In this part, we load the dataset data.csv and split it into training and testing subsets. Then, we develop a logistic regression model based on the training data using scikit-learn, utilizing only Feature1 and Feature2. After that, we plot the data points and the decision boundary of the model. Finally, we evaluate the model on the testing data and report its accuracy.

# Part B: Logistic Regression Without Scikit-learn
- Here, we implement logistic regression from scratch. We use the same training and testing data splits as in Part A and develop a logistic regression model based on the training data using only Feature1 and Feature2. We display the cost (loss) as a function of iterations during the training process. Then, we plot the data points and the decision boundary of our model. Finally, we evaluate the model on the testing data and report its accuracy.

# Part C: Logistic Regression with Feature Engineering (Scikit-learn)
- In this part, we enhance the dataset by adding new features that are at a higher degree of one of the original features (e.g., Feature1^2, Feature1 * Feature2). We use scikit-learn to develop a logistic regression model based on the enhanced training data. We plot the data points and the decision boundary of the model and evaluate its performance on the testing data, reporting its accuracy.

# Part D: Logistic Regression with Feature Engineering (Without Scikit-learn)
- Here, we use the enhanced dataset from Part C and implement logistic regression from scratch to develop a model based on the enhanced training data. We display the cost (loss) as a function of iterations during the training process, plot the data points and the decision boundary of our model, and evaluate its performance on the testing data, reporting its accuracy.
