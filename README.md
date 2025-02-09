# DataAnalysis

Here I worked on a dataset, consisting of 458 rows and 9 columns.The tasks I did include preprocessing the dataset, analyzing the data, and presenting your findings graphically.
Here's a breakdown of the steps I followed:

Preprocessing:
1. Correct the data in the "height" column by replacing it with random numbers between 150 and 180 using np.random.randint() function. Ensure data consistency and integrity before proceeding with analysis.

Analysis Tasks:
1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.
   
2. Segregate employees based on their positions within the company.
   a. Method : The total number of employees are found with respect to the position using value_counts() method grouped by position.
   b. A pie chart is plotted to show the insights.
   c. Findings/Insigts : From the  pie chart it is visible that the highest number of employees are present in 'SG' position(22.3%, 102 employees) and lowest in 'C' 
   position(17.2%, 79 employees).
  
3. Identify the predominant age group among employees. 
   a. Method:Age group is found using 'cut()' method to segment and sort data values into bins.
   b. age_group_distribution and predominant_age_group is found using 'value_counts()' of age_groups and 'idxmax()' of age_group_distribution respectievly.
   c. A bar chart is plotted to find Age Group Distribution.
   d. Findings/Insigts: Age group '20-25' has highest number of employees(179).
  
4. Discover which team and position have the highest salary expenditure. 
   a.  Method:Highest salary with respect to position and team are found using 'sum()' and 'idmax()' functions.
   b. A line chart is plotted to visualize the findings.
   c. Findings/Insigts: Team with highest salary expenditure: Cleveland Cavaliers and Position with highest salary expenditure: C
   
5. Investigate if there's any correlation between age and salary, and represent it visually. 
   a. Method: Correlation between age and salary are found using 'corr()'
   b. A scatterplot graph if used to represent the findings.
   c. Findings/Insights:Correlation between Age and Salary is 0.21400941226570971
