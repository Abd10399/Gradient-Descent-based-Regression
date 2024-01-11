# Gradient-Descent-based-Regression
Linear &amp; Logistic Regression Implementation with Analysis on Boston &amp; Wine Datasets

## Implementation Details
Implemented the analytical Linear Regression model using a closed form solution and compared the performance with a stochastic gradient descent regression model on the Boston data set. Further implemented multiclass Logistic Regression using gradient descent and trained it on the wine dataset for classification prediction.

## Basic Outline
In this project, the two foundational models of Machine Learning: Linear Regression and Logistic Regression were
implemented. Two types of linear regression (analytical and mini-batch stochastic gradient descent (SGD)) and
two types of softmax logistic regression (gradient descent and mini-batch SGD) were implemented and compared
in performance on the Boston Housing Dataset for linear regression models and the Wine Dataset for logistic
regression models. The performance of linear regression models was measured using the mean squared error
(MSE), while the performance of logistic regression models was measured using accuracy, precision, recall, and f1
scores. The performance of each model was analyzed across a variety of hyper-parameters such as the training
dataset size, mini-batch size, and learning rate. The findings were then used to determine which models with
which hyper-parameters perform best on each dataset. It was concluded that the Boston Housing Dataset is best
modeled using mini-batch SGD linear regression with the training dataset being a random 60% of the original
dataset, a batch size of 2, and a learning rate of 0.002. A lowest MSE of 18.5512 was achieved using these hyper-
parameters. It was also concluded that the Wine Dataset is best modeled using mini-batch SGD logistic regression
with a maximum average accuracy of 0.9861 for each class measured while the training dataset size was 60%, the
batch size was 128, and the learning rate was 0.006. An implementation of the momentum optimizing technique
was also added in the hyper-parameters Model to allow faster convergence.

## Results and Conclusion
In this study, Linear and Logistic Regression models were optimized using various hyper-parameters on the Boston
Housing and Wine datasets, respectively. Mini-batch SGD consistently outperformed other implementations,
showcasing its adaptability in both linear and logistic regression tasks. Specifically, the Boston Housing Dataset
favored mini-batch SGD linear regression with hyper-parameters achieving the lowest MSE of 17.2029. Similarly,
the Wine Dataset was best represented by mini-batch SGD logistic regression, reaching an impressive accuracy
of 0.9861. The findings suggest the versatility of the SGD approach, and future research could further explore
momentum optimization and integration of Gaussian basis functions to enhance performance.
