# Sonar-data-classifier-Neural-Networks

The aim of this classifier is  distinguish between rocks and metal structures such as sea mines on the seafloor. The dataset contains 111 patterns obtained by bouncing sonar signals off a metal cylinder at various angles and under various conditions and 97 patterns obtained from rocks under similar conditions.

Each pattern is a set of 60 numbers in the range 0.0 to 1.0. The label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder).

# Project Overview:
In this project you will apply unsupervised learning techniques on product spending data collected for customers of a wholesale distributor in Lisbon, Portugal to identify customer segments hidden in the data. You will first explore the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. Afterwards, you will preprocess the data by scaling each product category and then identifying (and removing) unwanted outliers. With the good, clean customer spending data, you will apply PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. Finally, you will compare the segmentation found with an additional labeling and consider ways this information could assist the wholesale distributor with future service changes.This project is designed to give you a hands-on experience with unsupervised learning and work towards developing conclusions for a potential client on a real-world dataset. Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. Being equipped with this information can assist a company engineer future products and services that best satisfy the demands or needs of their customers.



### Install
This project requires Python 3 and the following Python libraries installed:
- NumPy
Pandas
matplotlib
scikit-learn
You will also need to have software installed to run and execute an iPython Notebook

### Run
In a terminal or command window, navigate to the top-level project directory creating_customer_segments/ (that contains this README) and run one of the following commands:

ipython notebook customer_segments.ipynb jupyter notebook customer_segments.ipynb

This will open the iPython Notebook software and project file in your browser.

### Concepts explored in this project:

Unsupervised learning algorithms like K-Means Clustering and Gaussian Mixture Model Clustering
Feature Scaling
Dimensionality reduction using Principle Component Analysis
Outlier identification and removal
Silhouette scores
Relevant Classes:

Intro to Machine Learning

### Getting Started
To view the project, open customer_segments.html in a web browser.

### Data
The dataset used in this project is included as customers.csv. You can find more information on this dataset on the UCI Machine Learning Repository page.

# Resources on Dropout and early-stopping
 1.https://medium.com/@upendravijay2/how-does-dropout-help-to-avoid-overfitting-in-neural-networks-91b90fd86b20
 2.https://medium.com/@upendravijay2/early-stopping-to-avoid-overfitting-in-neural-network-keras-b68c96ed05d9
