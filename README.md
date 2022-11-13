# Matplotlib_Challenge
# Introduction
This project deals with screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice who were identified with SCC tumours received treatment with a range of drug regimens. Over the course of 45 days, tumour development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

In this activity, tables and figures needed for the technical report of the clinical study have been generated along with top-level summary of the study results.

# Instructions

1) To run the repo, use the following command
  git clone https://github.com/BharatGuturi/Matplotlib_Challenge.git
2) Input data is in Pymaceuticals\data
3) 'pymaceuticals_working' is the jupyter notebook created for study
4) 'mouse_data_complete' and 'mouse_data_complete_2' are the output csvs generated during the process of analysis

# Steps Involved:

1) Remove the duplicated data
2) Based on each pharmaceutical,calculating the mean, median, variance, standard deviation, and SEM of the tumor volume.
3) Check the mice'sex laying out.
4) Picking up four pharmaceuticals which have lowest results of SEM of the tumor volume, and comparing via box plots.
5) Checking the relation between tumour size and timeframe on the pharmaceutical which shows the best result.
6) Calculating the relation between tumour size and body size.

# Conclusions:

Few conclusions are as follows:
a) Overall trend showed a decrease in the tumour volume with respect to the time frame for the mice treated with Capomulin drug.
b) Overall trend showed a an increase in tumour volume with respect to the average weight of the mice under Capomulin regimen.
