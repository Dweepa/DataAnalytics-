
# Predicting the outcomes of visa applications

This project aims to predict the outcomes of three most popular classes of admission for visa applications, namely H1-B, L-1 and F-1. The work presented determines  how  visa  status  outcome  of  three  most  applied-to visa-categories (H1-B, L1, and F1) are influenced by attributes of user application metadata.

## Getting Started

1) Clone the repository
2) Make sure the jupyter notebook is installed and working
3) Follow the execution steps to replicate the results.

## Project description
#### 1.Preprocessing
The raw data, like any other real world data, contained many missing values. With this immensely colossal amount of missing values the prdiction process becomes arduous and unreliable. Thus a series of elimination and imputation processes were carried out to deal with this issue.

#### 2.Text Analysis
Our dataset also contained a lot of textual columns like job title, educational qualifications etc. Textual data of this amount cannot be analyzed directly. So the homogeneous data were grouped together to bring down the number of distinct ingressions from 12000+ to 87, which are not exorbitant to interpret.

#### 3.Encoding
Many machine learning algorithms cannot operate on label data directly. They require all input variables and output variables to be numeric. Therefore to ensure that all the models were able to fil the data, it was neccessary to convert the textual data into a numeric form.

#### 4.Dimensionality Reduction
It is very important for prediction to remove all the redundant features of the data set. As we are only interested in the attributes which actually contribute to some variance in our 'case_status' we removed the unneccessary columns.

#### 5. Classifier
We are using five different classification models for the data and comparing the results with actual values. According to our dataset, the neural network model gave us the best output and therefore we used that for further predictions.

#### 6. Result Analysis
In result analysis, we are taking the input from the user, and then using the k- nearest neighbors method to find the data entry which is closest to the data entered by the user. Thus predicting if it is likely for the user to get a certified visa application or not.

## Execution
Due to the size constraints, it wasn't possible to upload entire datasets. Thus, we have uploaded the first 5000 rows for each of the class but our actual data is about three times the size. To obtain the most proximate results to our values, run the classifier for class F-1.
Follow the steps of execution denoted by the folder numbers to get the desired output.

## Authors

Dweepa Honnavalli - 01FB16ECS138

Ishita Bhandari - 01FB16ECS143

Kavya Varma - 01FB16ECS162


