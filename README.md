# SVM_Gridsearch


Every machine learning model that you train has a set of parameters or model coefficients. The goal of the machine learning algorithm—formulated as an optimization problem—is to learn the optimal values of these parameters. 

In addition, machine learning models also have a set of hyperparameters. Such as the value of K, the number of neighbors, in the K-Nearest Neighbors algorithm. Or the batch size when training a deep neural network, and more.

These hyperparameters are not learned by the model. But rather specified by the developer. They influence model performance and are tunable. So how do you find the best values for these hyperparameters? This process is called hyperparameter optimization or hyperparameter tuning.

The two most common hyperparameter tuning techniques include:

Grid search
Randomized search
In this guide, we’ll learn how Grid search techniques work and their scikit-learn implementation
