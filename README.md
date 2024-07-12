Problem statement
Diabetes dataset is one of the datasets available in sklearn. The diabetes dataset consists of 10 physiological variables (age, sex, weight, blood pressure) measure on 442 patients, and an indication of disease progression after one year.

You are given a Training dataset csv file with X train and Y train data. As studied in lecture, your task is to come up with Linear Regression training algorithm and thus predictions for the test dataset given.

Read Instructions carefully -

1. Use Linear Regression(in scikit learn) as a training algorithm and submit results predicted by that.
2. Files are in csv format, use genfromtxt function in numpy to load data from csv file. Similarly you can use savetxt function to save data into a file.
3. Submit a csv file with only predictions for X test data. File should not have any headers and should only have one column i.e. predictions.  Also prediction values in file should be upto **5** decimal places.
4. Upon submission of predictions, the score you will get is based on coefficient of determination.
