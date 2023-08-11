# Hiring-Analytics

**OVERVIEW**

1. Hiring process is the fundamental and the most important function of a company. Here, the MNCs get to know about the major underlying trends about the hiring process. Trends such as- number of rejections, number of interviews, types of jobs, vacancies etc. are important for a company to analyse before hiring freshers or any other individual.

2. As a Data Analyst, it is important to find good trends in the Hiring data set so as to enable the senior managers to fill in the vacant seats if available with the right amount of salary provided to each individual.

**APPROACH**

1. _**Step 1**_: In this step the data is to be cleaned. Exploratory data analysis is performed to remove the date column as it is unnecessary to provide the answers to the given questions.
2. _**Step 2**_: In this step, box plot of seaborn library is used to check the outliers. It is found that the Salaries between 1000 and 1,00,000 are the necessary values. The other records are deleted.
3. _**Step 3**_: In this step, the null value of Offered Salary column is handled by replacing it with the mean. The missing values of the gender are left unhandled as that does not contribute much in the assessment as compared to the numeric values.
4. _**Step 4**_: The table is checked for any duplicate values. There are no duplicate values and now the data summary is drawn by using pivot Tables.
5. _**Step 5**_: I formed five pivot tables in new excel sheets to draw insights

**RESULT**

1. Insight 1: The male counter parts are hired more than the females. The data shows that 25% more males are working in the company than the females.
2. Insight 2: The average salary of each department is shown and different filters can be used to see which department is spending the maximum amount in terms of salaries. 
The post c-10 is allocated highest number of salaries.
3. Insight 3: A new pivot rule is used for creating class intervals and a histogram is created to display the count of salaries offered in the particular range. 
4. Insight 4: The number of people working in each department is portrayed using pie chart with each slice representing the percentage of the total number of employees available
5. Insight 5: The different charts represent the number of employees in each post tier. c9 is the largest tier with 1695 employees followed by c5.

**LEARNING**

1. Pivot tables, filters, aggregates and groupings
2. Charts and customization of charts
3. Exploratory Data Analysis using Google sheets and Python.

**THE END**
