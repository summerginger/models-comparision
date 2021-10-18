# models-comparision (module 19.5.3)
### Logistic Regression Vs. a Basic Neural Network

Neural networks are prone to overfitting and can be more difficult to train than a straightforward logistic regression model.
And if dataset has only a few features, neural networks may be overcomplicated. In comparison, logistic regression models are easier to dissect and interpret than their neural network counterparts, which tends to put more traditional data scientists and non-data experts at ease. In contrast, neural networks (and especially deep neural networks) thrive in large datasets. 

Datasets with thousands of data points, or datasets with complex features, may overwhelm the logistic regression model, while a deep learning model can evaluate every interaction within and across neurons. Therefore, the decision between using a logistic regression model and basic neural network model is nuanced and, in most cases, a matter of preference for the data scientist.

### Support Vector Machine Vs. Deep Learning Model 

SVMs are supervised learning models that analyze data used for regression and classification.

![image](https://user-images.githubusercontent.com/82733723/132873474-631a1f90-1722-4931-b325-c979f544a88f.png)

SVMs, like neural networks, can analyze and interpret multiple data types, such as images, natural language voice and text, or tabular data. SVMs perform one task and one task very well—they classify and create regression using two groups. In contrast, neural networks and deep learning models are capable of producing many outputs, which means neural network models can be used to classify multiple groups within the same model. Over the years, techniques have been developed to create multiple SVM models side-by-side for multiple classification problems, such as creating multiple SVM kernels. However, a single SVM is not capable of the same outputs as a single neural network.
SVMs have an advantage over neural network and deep learning models:
Neural networks and deep learning models will often converge on a local minimum. In other words, these models will often focus on a specific trend in the data and could miss the "bigger picture."
SVMs are less prone to overfitting because they are trying to maximize the distance, rather than encompass all data within a boundary.

Both models take similar amounts of time to train on the input data. The only noticeable difference between the two models is implementation—the amount of code required to build and train the SVM is notably less than the comparable deep learning model. As a result, many data scientists will prefer to use SVMs by default, then turn to deep learning models, as needed.

# Random Forest Vs. Deep Learning Model

Random forest is a supervised ensemble learning model that combines decision trees to analyze input data.
forest models are easy to interpret, and they can easily handle outliers and nonlinear data

![image](https://user-images.githubusercontent.com/82733723/132889545-5aa65ea1-5eaa-4024-bf8f-c54d65d207d9.png)

random forest models will only handle tabular data, so data such as images or natural language data cannot be used in a random forest without heavy modifications to the data
Neural networks can handle all sorts of data types and structures in raw format or with general transformations (such as converting categorical data).
Random forest models are dependent on each weak learner being trained on a subset of the input data. Once each weak learner is trained, the random forest model predicts the classification based on a consensus of the weak learners. In contrast, deep learning models evaluate input data within a single neuron, as well as across multiple neurons and layers.

