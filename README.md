# Sonar-data-classifier-Neural-Networks

The aim of this classifier is  distinguish between rocks and metal structures such as sea mines on the seafloor. The dataset contains 111 patterns obtained by bouncing sonar signals off a metal cylinder at various angles and under various conditions and 97 patterns obtained from rocks under similar conditions.

Each pattern is a set of 60 numbers in the range 0.0 to 1.0. The label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder).

## Getting Started
To view the project, open report.html in a web browser.

### Install
This project requires Python 3 and the following Python libraries installed:
- NumPy
- Pandas
- matplotlib
- scikit-learn
- keras
- You will also need to have software installed to run and execute an iPython Notebook

### Run
In a terminal or command window, navigate to the top-level project directory Sonar-data-classifier-Neural-Networks/ (that contains this README) and run one of the following commands:

- ipython notebook Sonar_classifier.ipynb 
- jupyter notebook Sonar_classifier.ipynb
This will open the iPython Notebook software and project file in your browser.

### Concepts explored in this project:
- Early-stopping
- Dropout

### Data
The dataset used in this project is included as sonar.csv. You can find more information on this dataset on the UCI Machine Learning Repository page.

# Resources on Dropout and early-stopping
 1.https://medium.com/@upendravijay2/how-does-dropout-help-to-avoid-overfitting-in-neural-networks-91b90fd86b20
 2.https://medium.com/@upendravijay2/early-stopping-to-avoid-overfitting-in-neural-network-keras-b68c96ed05d9
