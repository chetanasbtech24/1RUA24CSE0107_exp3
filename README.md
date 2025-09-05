Descriptive Statistics Experiment
Overview
This notebook explores descriptive statistics using the Fortune 500 dataset and an Income-Expenditure dataset. The goal is to compute and interpret various statistical measures to understand the central tendency, dispersion, and shape of the data distributions.

Table of Contents
Introduction to descriptive statistics
Measures of central tendency
Measures of dispersion
Dataset description
Import libraries
Import dataset
Exploratory data analysis
Descriptive statistics with describe() function
Computation of measures of central tendency
Computation of measures of dispersion or variability
Computation of measures of shape of distribution
Income-Expenditure Dataset Analysis
Datasets Used
Fortune 500 Dataset: Contains revenue and profit figures for Fortune 500 companies along with their rank and year. (Source: data.world)
Income-Expenditure Dataset: Contains monthly household income and expense, family size, EMI/rent, annual income, highest qualification, and number of earning members. (Source: Provided locally as 'Inc_Exp_Data.csv')
Analysis Performed
The notebook performs the following analyses:

Descriptive Statistics: Computes and interprets mean, median, mode, variance, standard deviation, range, IQR, skewness, and kurtosis for relevant variables in the Fortune 500 dataset.
Exploratory Data Analysis: Includes checking dataset dimensions, previewing data, viewing data types, and checking for missing values.
Income-Expenditure Dataset Analysis: Addresses specific questions related to:
Central tendency and range of income and expense.
Income-to-expense ratio and disposable income.
Average family size and dependency ratio.
EMI/rent as a percentage of income.
Consistency of annual income.
Average income by highest qualification.
Detection of outliers in monthly income.
Correlation between monthly income and expense, and between earning members and monthly income.
Key Findings
The Revenue (in millions) in the Fortune 500 dataset is positively skewed.
Discrepancies were found between the provided Annual_HH_Income and the calculated annual income from Mthly_HH_Income in the Income-Expenditure dataset.
Higher qualification generally correlates with higher average monthly household income.
A moderate correlation exists between monthly household income and monthly household expense, and between the number of earning members and monthly household income.
Here's some content you could use for a LinkedIn post about your descriptive statistics experiment:

Exploring Descriptive Statistics: Insights from Fortune 500 and Household Income Data

Just wrapped up an interesting project diving into descriptive statistics using two distinct datasets: the Fortune 500 and a Household Income/Expenditure dataset.

Descriptive statistics provide fundamental insights into data, summarizing key features through measures of central tendency (mean, median, mode), dispersion (variance, standard deviation, range, IQR), and shape (skewness, kurtosis).

Key takeaways from the analysis include:

📊 Fortune 500 Data:

Examined the distribution of Revenue (in millions), finding it to be positively skewed.
Calculated various measures of spread, including variance, standard deviation, and IQR.
🏠 Household Income & Expenditure Data:

Analyzed the central tendency and range of monthly income and expenses.
Investigated the income-to-expense ratio and identified households with high EMI/rent percentages and low disposable income.
Explored family structure by looking at the average number of members and dependency ratios.
Verified the consistency of annual income calculations.
Grouped households by highest qualification to see the correlation with average monthly income (Spoiler: Higher qualification generally correlates with higher income!).
Identified potential outliers in monthly income using the Z-score method.
Computed correlations between monthly income and expense, and between earning members and monthly income, finding moderate relationships.
This experiment reinforced the power of descriptive statistics in quickly understanding the basic characteristics and potential patterns within a dataset before moving on to more complex analyses.

Feel free to share your thoughts or similar experiences with descriptive statistics in the comments below!

DataAnalysis #DescriptiveStatistics #DataScience #Pandas #Python #StatisticalAnalysis #Fortune500 #HouseholdFinance #DataInsights #Learning
