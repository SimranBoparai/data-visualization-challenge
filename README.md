# data-visualization-challenge
Week 5 Assignment

# Prerequisites
Before you work on the data visualization challenge, ensure you complete the following requirements:
- You have installed Python or Jupyter Notebook/Lab with the matplotlib, numpy, and scipy libraries 
- Visual Studio Code can be used to complete this challenge
- You are working on a Windows or MAC OS machine
- Create a new repository named 'data-visualization-challenge' in GitHub for the challenge with a README file

# Repository Setup
Complete the following steps to create a new repository:
1. Create a new repository for this challenge called 'data-visualization-challenge' with a README. 
2. Clone the new repository SSH Key to your computer.
3. Inside your local Git repository (Git Bash), create a ''data-visualization-challenge folder.
4. Inside the folder, copy and paste the necessary folders/files for the challenges:
    - Data folder with two CSV datasets
    - pymaceuticals_starter
5. Git Add, Commit, and Push these changes to GitHub. 

 # About the Challenge
 The data visualization challenge analyses potential treatments for a pharmaceutical company from the given datasets in two different CSV files. The following dimensions are analyzed through calculations and charts to gain insights into mice and treatment performance. The sections include:

Data Preparation:
	- Import and merge the two datasets
	- Clean the data and display a new data frame 
	- Display the number of unique mice IDs

Summary Statistics:
	- Calculate the mean, median, variance, standard deviation, and standard error for each drug regimen and display a data frame

Bar and Pie Charts:
	- Create two bar charts
		- one using the Pandas method 
		- other using Matplotlib's pyplot method  
	- Create two pie charts
		- one using the Pandas method 
		- other using Matplotlib's pyplot method  

Quartiles, Outliers and Boxplots:
	- Use the groupby method to calculate the greatest time point for each mouse, then merge the new data frame with the original clean data frame
	- Create a list holding four treatments (Capomulin, Ramicane, Infubinol, and Ceftamin) and an empty list 
	- Loop through each drug in the list in a merged data frame, which appends volume to an empty list
	- Use Matplotlib to create a box plot that shows the final distribution of the tumor volume for each treatment
		- Identify the quartiles
		- Calculate lower and upper bound and IQR

Line and Scatter Plots:
	- Use Matplotlib to create a line plot using the given Mouse ID and  tumor volume over time 
	- Use Matplotlib to create a scatter plot of mouse weight versus the average observed tumor volume for the Capomulin treatment (use the mean method)

Correlation and Regression:
	- Calculate the correlation and linear regression between mouse weight and average observed tumor volume for the Capomulin treatment
	- Use Matplotlib to plot the scatter plot and the linear regression line
 
Written Analysis

## Instructions
 - Following the structure of the starter code to complete the cells listed above. Use appropriate methods/functions to calculate specific statistical values required in the different sections. Generate charts for each section using Matplotlib using different data frames and calculated values to highlight the trends among drug regimens and mice characteristics. 

# Acknowledgement 
I want to mention the following individual and resources for their assistance and support throughout this assignment:
    - Instructor for hleping me debug the box plot and quartile section of my code when looping through different regimens.  
    - Ask the BCS Learning Assistant to explain the difference between specific Matplotlib functions and how to use them to plot data accurately. 
    - Study group member(s) who helped me debug my code to find the duplicated Mouse ID.