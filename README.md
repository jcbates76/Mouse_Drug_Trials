# Mouse_Drug_Trials
This project utilizes matplotlib functionality.  

## Background
In this project, data is taken from two files (mouse metadata and study data) and analysis is performed to review the effectiveness of different drug regimens.  

## Prepare the data for analysis
Merge the data from the two files, look for mouse ID's with duplicated timepoints, and remove that mouse ID.  

Using the cleaned-up data, generate a table of summary statistics (mean, median, variance, standard deviation and standard error or mean) for tumor size for each drug regimen.  

## Bar and Pie Charts
Generate a bar plot using both Pandas DataFrame.plot() and Matplotlib's pyplot that shows the total number of timepoints for all mice tested for each drug regimen throughout the course of the study. 

![Timepoints_Per_Drug_Regimen](https://user-images.githubusercontent.com/94392882/188527474-f6bb9dc6-9735-49fc-9554-11dbe41d1a09.png)

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

![Distribution_of_Mice_Gender](https://user-images.githubusercontent.com/94392882/188527496-3313a3aa-457d-4159-bc02-e124aff76e79.png)

## Boxplots
Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.  

Calculae the quartiles, IQR and determine if there are any outliers in the data.

Generate a box and whisker plot for the final tumor volume for all four treatment regimens.  

![Tumor_Size_per_Drug_Regimen](https://user-images.githubusercontent.com/94392882/188526986-287b409d-3310-44f1-a4a2-bd43a1476b96.png)

## Line Chart, Scatter Chart, Correlation and Regression
Select a mouse that was treated with Capomilun and generate a line plot of tumor volume vs. time point for that mouse.  

![Capomilin_Tumor_Volume_vs_Timepoint](https://user-images.githubusercontent.com/94392882/188527511-effdbbd3-062b-4028-a858-46611a06398f.png)

Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatement regimen.  

![Capomulin_Tumor_Volume_vs_Mouse_Weight](https://user-images.githubusercontent.com/94392882/188527528-f4603819-7ec1-49a2-b11e-9644b2a45c1a.png)

Calculate the correlation of coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.  Plot the linear regression model on top of the previous scatter plot.  

![Capomulin_Tumor_Volume_vs_Mouse_Weight_Regression](https://user-images.githubusercontent.com/94392882/188527540-98f862f0-728c-4aac-9762-35866bc21844.png)

## Analysis
Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data.  
