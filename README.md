<<<<<<< Updated upstream
Getting and Cleaning Data: Course Project
Introduction

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization. What follows first are my notes on the original data.

About the raw data

The features (561 of them) are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.

The same holds for the training set.

About the script and the tidy dataset

I created a script called run_analysis.R which will merge the test and training sets together. Prerequisites for this script:

the UCI HAR Dataset must be extracted and..
the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

About the Code Book

The CodeBook.md file explains the transformations performed and the resulting data and variables.
=======
Getting and Cleaning Data
==========================================

This repository hosts the R code and documentation files for the Data Science's track course "Getting and Cleaning data", available in coursera.

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

The code takes for granted all the data is present in the same folder, un-compressed and without names altered.

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps. They can be launched in RStudio by just importing the file.

The output of the 5th step is called `tidy.txt`, and uploaded in the course project's form.
>>>>>>> Stashed changes
