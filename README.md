# ECE228-Group88
Steam Volume Prediction for Industrial Boilers

The programme is based on the project 'Steam Volume Prediction for Industrial Boilers'.
It completes the required prediction by several models.

The main programme file is '88SW.ipynb' and other files include 'steam_test.txt' and 'steam_train.txt'
which are respectively the test and train dataset.

The programme can be runned as long as all the three flies are upload into the same fold of  
notebook.

## 1 Data Preprocess

### 1.1 Read Datasets
Read the datasets and show the first 5 rows of data

### 1.2 Data Distribution
Find out the data distribution of 'V0'...'V37'

### 1.3 Data Cleaning
Dropout feature "V5","V9","V11","V14","V17","V21","V22","V28" for their uneven distribution on Train/Test sets.

### 1.4 Data visualization
Show the normality of rest features

### 1.5 Correlation coefficient
Find out the correlation coefficient

### 1.6 Normalize
Do the normalization on the data

### 1.7 Box-Cox transformation
Show the influence of Box-Cox transformation on the distribution of the data, then do the transformation

### 1.8 features of the target
Do the logarithm transformation on the target data to improve its normality

### 1.9 Elinminate abnormal data with OneClassSVM

## 2 Models
### 2.1 split train and validation set
### 2.2 Linear Regression
### 2.3 Gradient Boosting Regression
### 2.4 Ridge
### 2.5 MLP Regression
