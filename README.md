# matplotlib_challenge
This project utilizes matplotlib functionality.  

## Background
In this project, data is taken from two files (mouse metadata and study data) and analysis is performed to review the effectiveness of different drug regimens.  

## Prepare the data for analysis
Merge the data from the two files, look for mouse ID's with duplicated timepoints, and remove that mouse ID.  

Using the cleaned-up data, generate a table of summary statistics (mean, median, variance, standard deviation and standard error or mean) for tumor size for each drug regimen.  

## Bar and Pie Charts
Generate a bar plot using both Pandas DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study. 

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

## Boxplots
Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.  

Calculae the quartiles, IQR and determine if there are any outliers in the data.

Generate a box and whisker plot for the final tumor volume for all four treatment regimens.  


## Line Chart, Scatter Chart, Correlation and Regression
Select a mouse that was treated with Capomilun and generate a line plot of tumor volume vs. time point for that mouse.  

Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatement regimen.  

Calculate the correlation of coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.  Plot the linear regression model on top of the previous scatter plot.  

## Analysis
Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data.  
