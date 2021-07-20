# Breast-cancer-detection
This is a practical case study of logistic regression. Logistic regression has many applications in data science, but in the world of healthcare, it can really drive life-changing action. In this case study, we apply a logistic regrression model on a real-world dataset and predict whether the tumor is benign(not breast cancer) or malignant(breast cancer) based off its characteristics. 

The different independent variables in the dataset are   
* Clump thickiness.
* Uniformity of cell size.
* Uniformity of cell shape.
* Marginal adhesion.
* Single epithelial cell.
* Bares Nuclei.
* Bland chromatin.
* Normal nucleoli.
* Mitoses.   

## About Dataset
The dataset used for this case study was extracted from https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29   

### **Attribute Information**   

1. Sample code number: id number
2. Clump Thickness: 1 - 10
3. Uniformity of Cell Size: 1 - 10
4. Uniformity of Cell Shape: 1 - 10
5. Marginal Adhesion: 1 - 10
6. Single Epithelial Cell Size: 1 - 10
7. Bare Nuclei: 1 - 10
8. Bland Chromatin: 1 - 10
9. Normal Nucleoli: 1 - 10
10. Mitoses: 1 - 10
11. Class: (2 for benign, 4 for malignant) 


### **Steps Involved** 

1. Importing the libraries.
2. Importing the dataset.
3. Splitting the dataset into training and testing sets.
4. Training the logistic regression model on the training set.
5. Predicting the test result.
6. Creating the confusion matrix.
7. Calculating the accuracy with k-fold cross validation.
___

## Observation   
The result of the confusion matrix are as follows:  

|   84  |   3	|
|---	|---	|
|   3	|  47 	|

Where,   
True positive = 84   
False negative = 3   
True negative = 47   
False positve = 3    

The overall accuaracy of the classification model using k-fold validation was observed to be 96.70 %.   

The standard deviation was observed to be 1.97%.
___   
>Note* : The dataset filename is "breast_cancer.csv".

