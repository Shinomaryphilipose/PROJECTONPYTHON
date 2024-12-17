After completing the Python module, in Data Science and Machine Learning, we got a data set from ABC company, consisting of 458 rows and 9 columns. 
The company requires a comprehensive report detailing information about their employees across various teams. My tasks include preprocessing the dataset,
analyzing the data, and presenting my findings graphically.
The given data set ia also uploaded as myexcel-myexcel.csv.csv.
At first I have to import all the necessary libraries needed such as pandas,seaborn,matplotlib,numpy etc.
Using Pandas the data set is loaded.
In the original data set given the 'Height' column was filled with dates.Before preprocessing I replaced the dates with height ranging from 150 to 180 using random function.
For Data Cleaning and Data Analysing i used the following steps:
a)Understanding the data using desribe(),info(),and shape() functions.
b)Found missing data using isnull() and handled it with fillna() function (instead of using dropna() function).
c)Checked duplicates using duplicated() function.
d)Checked data types.
e)Checked outliers using data visualization using box plot.
Determined the distribution of employees across each team and calculated the percentage split relative to the total number of employees.There are 30 teams and 19 to 14 employees 
are there in each team.
Segregated employees based on their positions within the company using groupby() function. 
Identified the predominant age group among employees.Predominent age group is 20-25 
Discovered which team and position have the highest salary expenditure. Using scatter plot.
Investigated if there's any correlation between age and salary, and represented it visually using heat map.  
