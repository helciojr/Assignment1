Assignment 1: Air Pollution

Introduction
For this first programming assignment you will write three functions that are meant to interact with dataset that accompanies this assignment. The dataset is contained in a zip file specdata.zip that you can download from the Coursera web site.
For this programming assignment you will need to unzip this file and create the directory 'specdata'. 

Write a function named 'pollutantmean' that calculates the mean of a pollutant (sulfate or nitrate) across a specified list of monitors.

Write a function that reads a directory full of files and reports the number of completely observed cases in each data file.Please save your code to a file named complete.R

Write a function that takes a directory of data files and a threshold for complete cases and calculates the correlation between sulfate and nitrate for monitor locations where the number of completely observed cases (on all variables) is greater than the threshold. Please save your code to a file named corr.R.

This assignment will be graded using unit tests executed via the submit script you run on your computer. To obtain the submit script, run the following code in R:
source("http://d396qusza40orc.cloudfront.net/rprog%2Fscripts%2Fsubmitscript1.R")
