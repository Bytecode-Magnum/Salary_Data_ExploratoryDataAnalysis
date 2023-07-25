# Supermart_Sales_EDA
### Project Title: Exploratory Data Analysis and Data Visualization

## Introduction:
In this project, I conducted an exploratory data analysis (EDA) and data visualization on a dataset containing information about individuals, including their age, gender, education level, job title, years of experience, and salary. The main goal of this project was to gain insights, patterns, and trends from the data and present them through visualizations to facilitate better understanding and decision-making.

## Data Description:
The dataset consisted of 1779 records, each representing a unique individual. The attributes included:

Age: The age of the individual in years.
Gender: The gender of the individual (Male/Female).
Education Level: The highest level of education attained by the individual (Bachelor's, Master's, PhD, or NaN for missing values)
Job Title: The job title or role of the individual.
Years of Experience: The number of years of professional experience.
Salary: The salary of the individual (in dollars per year), with some missing values represented as NaN.

[Salary DataSet](https://github.com/Bytecode-Magnum/Salary_Data_ExploratoryDataAnalysis/blob/main/Salary_Data.csv)

## Exploratory Data Analysis:
   
During the exploratory data analysis phase, I began by checking the general structure of the dataset, looking for any missing values, and assessing the distribution of the numerical variables (age, years of experience, and salary). I handled missing values appropriately, ensuring they didn't skew the analysis. Descriptive statistics were computed to understand the central tendencies and spreads of the numerical attributes.

Next, I performed various univariate and bivariate analyses to gain insights into individual attributes and their relationships. For example, I explored the distribution of education levels among different genders and analyzed the salary distribution based on job titles. Furthermore, I investigated any correlations between age, years of experience, and salary to identify potential patterns.
### [Data Processing](https://github.com/Bytecode-Magnum/Salary_Data_ExploratoryDataAnalysis/blob/main/Salary_dataset.ipynb) 

## Data Visualization:

Data visualization played a crucial role in this project as it helped present complex findings in a more accessible manner. I utilized various visualization techniques, such as bar charts, histograms, scatter plots, and box plots, to showcase different aspects of the data.   
Plotly.express is used for data analysis, but github dont render dynamic plots,so below is link for nbviewer.
 [Data visulization](https://nbviewer.org/github/Bytecode-Magnum/Salary_Data_ExploratoryDataAnalysis/blob/main/Sales_dataset_Data_Visualization.ipynb)

## Libraries:
Here are the Python packages I used for the project:                                                           [Pandas](https://pandas.pydata.org/)      
[Seaborn](https://seaborn.pydata.org/)          
[Numpy](https://numpy.pydata.org/)  
[Plotly express](https://plotly.com/python/)

## Insights and Conclusion:
Through exploratory data analysis and data visualization, I uncovered several key insights about the dataset:

The majority of individuals held a Bachelor's or Master's degree.
There was a gender imbalance, with more males represented in the dataset.
Job titles ranged from entry-level positions, such as Data Analyst and Software Engineer, to senior roles like Senior Manager and Director.
Salaries varied widely based on job titles and years of experience.




