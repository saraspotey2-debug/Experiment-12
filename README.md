# Experiment-12
# Aim
Categorical Data Analysis Using Python
# Theory
1. Categorical data analysis is the study of data that represents categories or groups. In Python, it is performed using libraries like pandas and numpy to calculate frequencies, visualize data, and analyze relationships. It is widely used in surveys, business analysis, and machine learning.
2. import pandas- This line imports the pandas library.Pandas is used for data handling and analysis.
3. df.shape- It returns the dimensions of the dataframe in the form of (rows,columns).
4. df.size- It returns the total number of elements (values) in the DataFrame.(size=rows*columns).
5. df.info() is a function used to get a summary of a dataframe.It gives quick information about the structure of the dataset.It gives number of entries (rows), column names, non-null values, data types and memory usage.
6. df.head-It is used to display the first few rows of a dataframe.By default, it shows first 5 rows.
7. df.tail-It is used to display the last few rows of a dataframe.By default, it shows last 5 rows.
8. df.sample(5) is used to select random rows from a dataframe.It returns 5 random rows from the dataset.
9. df.isnull().sum()-It is used to check missing (null) values in each column of a datarfame.
10. df.duplicated().sum()-It is used to find the number of duplicate rows in a dataframe.
11. df.nunique() is used to count the number of unique (distinct) values in each column of a dataframe.
12. df['Grade'].value_counts()-It returns the frequency (count) of each unique category in the 'Grade' column.
13. df['Gender'].value_counts()-It returns the frequency (count) of each unique category in the 'Gender' column.Similarly we can calculate for other columns like department.
14. df['Grade'].value_counts(normalize=True)*100-It returns the percentage distribution of each category in the 'Grade' column.
15. pd.crosstab(df['Gender'],df['Grade'])-It creates a contingency table showing the frequency of each combination of Gender and Grade.Similarly, 'Department' vs 'Gender' and 'Department' and 'Grade' can be implemented.
16. pd.crosstab(df['Department'],df['Grade'],normalize='index')*100)-It shows the row-wise percentage distribution of Grade within each Department.
17. df.groupby('Department')['Grade'].value_counts()-It returns the count of each Grade within each Department (group-wise frequency).
18. pd.DataFrame(data)-It creates a DataFrame from the given data using the pandas library.
19. df['Category'].value_counts()-It returns the frequency (count) of each unique category in the 'Category' column.In similar way unique payment methods can be calculated.
20. df['Category'].value_counts(normalize=True)*100-It returns the percentage distribution of each category in the 'Category' column.
21. df['Category'].unique()-It returns all unique values (distinct categories) present in the 'Category' column.
22. 
