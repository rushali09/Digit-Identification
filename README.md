# Digit-Identification

This project focuses on recognizing handwritten digits (0-9) using Logistic Regression for multiclass classification.
The workflow includes data preprocessing, model training, and performance evaluation using metrics like accuracy and a confusion matrix. The project leverages Python libraries such as scikit-learn, NumPy, and Matplotlib.

Key Features:
Preprocessing: Normalization of pixel values for better model accuracy.
Multiclass classification using one-vs-rest (OvR) Logistic Regression.
Evaluation: Accuracy, confusion matrix.
Visualization of predictions and misclassifications.
The project is a simple yet effective implementation of Logistic Regression for solving digit identification problems.

Logistic Regression for multiclass classification is an extension of binary logistic regression to handle problems with more than two classes. It uses techniques like One-vs-Rest (OvR) or Softmax (Multinomial) to predict the probability of an input belonging to each class.

One-vs-Rest (OvR): A separate binary classifier is trained for each class, treating it as the positive class while others are negative. The class with the highest probability is chosen.
Softmax (Multinomial): A single model predicts probabilities for all classes simultaneously, ensuring the sum of probabilities across all classes equals 1.
This approach works well for tasks like digit recognition, text classification, and multi-class image categorization, using optimization techniques like Gradient Descent to minimize the loss. It assumes linear separability of classes and performs best when the data satisfies this condition.
