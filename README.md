# matplotlib-challenge-Module-5
# Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

# Summary
For this assignment I had to utilize python and matplotlib in order to analyze different drug effectiveness on the size of tumors in mice.  I merged the two initial csv files into one and created a summary statistics DataFrame to get the mean, median, variance, standard deviation, and SEM of the tumor volume.

I also created two bar charts and two pie charts using first the DataFrame.plot() method and second the pyplot method. The bar charts displayed the total number of timepoints for all mice tested for each of the different drug treatments and the pie charts displayed the distributions of female versus male mice.

I then calculate the quartiles and interquartile range to create a box plot and determine if there were any potential outliers in the data.

A line plot on the average tumor size of mouse l509 showed the tumor size change over time while the scatter plot demonstrated how there was positive correlation between the weight of a mouse and the average tumor volume.

The analysis and main code can be found in the pymaceuticals_main.ipynb
