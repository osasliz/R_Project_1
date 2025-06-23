# Expense Analysis

### Aim and Overview

The aim of this analysis is to provide insight into my monthly food expense for the year 2024. Therefore to carry out this analysis, I obtained my monthly expense data from my monthly bank account statement for the year 2024.

### Tools
- Excel - Data cleaning and preparation
- R - Data analysis

### Data Cleaning and Preparation
Initial data preparation phase, the following task was performed
1. Data loading
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data  analysis
Here I explore the data to answer the key question_
- What was my average monthly food expense for the year 2024?
- What month has the highest food expense?

### Data Analysis

```R
library(data.table)
library(ggplot2)

my_data <- fread("2024Bankstatement.csv")
view(my_data);
```

### Results
Food expense varies from month to month. The month of April had the highest food expense (calculated in Euros). 

![image](https://github.com/user-attachments/assets/c1808819-d9b3-4faf-b44b-2ee662166a22)


### Limitations
This project only compares a year food expense and therefore has limitation. Data used for this project are not broad enough to enable one explore better plot analysis and to compare yearly food expense.


### Recommendation
Base on the above limitations, I recommend:
- Data update with other years expenses
- Calculate the average yearly food expense.

### References
https://youtu.be/qjLHX3RCayI?si=-uyiF4gymljlJdtw
