Classifying Synthetic Data using Decision Trees A straightforward synthetic dataset of 1500 cases, created for a binary classification task, may be found in this repository. Class 0 has a uniform distribution, while Class 1 is constructed using three Gaussian distributions. The objective is to show how to categorize the examples using a Decision Tree classifier.

Creation of Datasets The dataset is created in Python using Matplotlib and NumPy. For Class 1, three Gaussian distributions are utilized, with means of [6,14], [10,6], and [14,14]. Over the range [0, 20], class 0 is formed with a uniform distribution.

Classification of Decision Trees The scikit-learn package is used to create a Decision Tree classifier. The classifier is trained on the training set of the dataset after it has been divided into training and testing sets. Next, the classifier's accuracy is assessed using the test set.
