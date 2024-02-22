# EDA-Project_Analysis-of-AMCAT-Data
Technologies Used: 
Python 
Pandas 
NumPy 
Matplotlib 
Seaborn 
SciPy

Project Details:

Data Collection:

The project uses a dataset containing information about salaries and job cities for software engineers.
The dataset is filtered to include only software engineers in the CSE specialization.

Outlier Removal:

Outliers in the salary data are identified and removed using the Interquartile Range (IQR) method to ensure the analysis is not skewed by extreme values.

ANOVA Analysis:

ANOVA (Analysis of Variance) is performed to test the hypothesis that the mean salaries for software engineers are the same across all metropolitan cities.
The F-test statistic and p-values are calculated for each city to determine if there are significant differences in salaries.

Multiple Testing Correction:

To account for multiple comparisons, the Benjamini/Hochberg method is applied to correct the p-values.
