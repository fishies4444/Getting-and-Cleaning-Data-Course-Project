Getting-and-Cleaning-Data-Course-Project
========================================
run_analysis.R

Script run_analysis.R can help you get mean data for Mean and Std columns of Human Activity Recognition Using Smartphones Dataset. To use it you should place script next to dataset folder in the R working directory. Also you can set data_path attribute if the included folder name is not where your data is.

Processing usualy takes less then one minute.

Result in dataset folder; file named tidy_data.txt.


Human Activity Recognition Using Smartphones Dataset

Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto. Smartlab - Non Linear Complex Systems Laboratory DITEN - Università degli Studi di Genova. Via Opera Pia 11A, I-16145, Genoa, Italy. activityrecognition@smartlab.ws www.smartlab.ws

Data Download link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip Description Download link: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Dependencies:

Script depends on reshape2 and data.table libraries and they will be installed automatically if needed.
