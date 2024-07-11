# Linear-Logistic-Regression-TensorFlow
Implementing and analyzing Linear and Logistic Regression models using TensorFlow for university admission prediction

1.Project Overview: This project involves performing linear and logistic regression using TensorFlow to predict the likelihood of university admissions based on applicants' features such as GRE scores, TOEFL scores, and CGPA.

2.Data Preprocessing: The dataset includes features with different value ranges, which are scaled using a standard scaler. The data is then converted into TensorFlow tensors to facilitate model training.

3.Linear Regression Model: A linear regression model is constructed using TensorFlow, with weights and bias initialized as TensorFlow variables. The model is trained using stochastic gradient descent (SGD) optimizer for 1000 epochs, and the mean squared error (MSE) is used as the loss function.

4.Logistic Regression Model: Logistic regression is implemented for binary classification. The target variable is converted to binary using a threshold, and the model is trained for 50 epochs. For multiclass classification, the target variable is binned into three categories (low, medium, high) and softmax activation is used.

5.Model Evaluation: The linear regression model is evaluated using the testing data, and MSE is printed. For logistic regression, the loss for each epoch is displayed, and accuracy is computed. Actual vs predicted probabilities are plotted using matplotlib.

6.Comparison with Other Models: The performance of linear and logistic regression models is compared using k-fold cross-validation. The effect of different learning rates on model performance is analyzed, and feature selection is performed based on correlation coefficients.

7.Submission and Results: The implementation includes code for data preprocessing, model training, evaluation, and comparison. The final submission consists of a cleaned Jupyter notebook and a readme file with group members' names and IDs. The results, including MSE, accuracy, and plots, are documented
