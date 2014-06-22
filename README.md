Peer-Assessments---Week-3---Getting-and-Cleaning-Data-Course-Project
====================================================================

This repo is a project for the Coursera course Cleaning and Getting Data

The README.MD explains what the run_analysis.R script does.

First, unzip the data from 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
then, rename the folder with "UCI HAR Dataset".

The folder "UCI HAR Dataset" and the run_analysis.R script must be both in the current working directory.

Inside RStudio do source("run_analysis.R")

Find the two output files are generated in the current working directory
tidy_first_merged_data.txt       :  data frame called cleanedData with 10299*68 dimension.
tidy_second_data_with_means.txt  :  data frame called result with 180*68 dimension

Read the file in RStudio with the command : ´ data <- read.table("tidy_second_data_with_means.txt") ´
It has 180 rows.

That´s all.

