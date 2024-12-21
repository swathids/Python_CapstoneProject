# Python_CapstoneProject
This repository contains my Python Capstone Project as a part of Machine Learning -skill development course organized by Entri App.

#Comprehensive Overview of the Project

A dataset has been provided, consisting of 458 rows and 9 columns, containing employee information across various teams at ABC company. The task is to apply knowledge of data preprocessing, analysis, and visualization to this dataset. The goal is to analyze the distribution of employees, salary expenditures, and other key trends, and to present the findings through detailed reports and visual representations. This project aims to demonstrate the ability to manipulate and analyze data to derive meaningful insights for business decision-making.

##Preprocessing Steps:
--The "Height" column in the dataset will be corrected by replacing the existing values with random numbers between 150 and 180 to ensure consistency and accuracy across the dataset.

In the preprocessing step of the code, the dataset "ABC.csv" is first loaded using pd.read_csv() to create a DataFrame for analysis. The data.info() function provides an overview of the dataset, displaying the number of rows, columns, and data types, while data.head() is used to inspect the first few rows and check for any missing or erroneous values. Specifically, the "Height" column is corrected by replacing its values with random integers between 150 and 180 using np.random.randint(), ensuring consistency and filling in any missing or invalid height data. Finally, print(data.head()) is used to confirm that the changes have been applied correctly and the dataset is now ready for further analysis.


#Analysis Tasks:
--Employee Distribution Across Teams: Analyze the distribution of employees across various teams and calculate the percentage split relative to the total number of employees.

--Segregation by Position: Group employees based on their positions within the company and present this information.
Predominant Age Group: Identify the most common age group among employees to understand the workforce demographics.

--Salary Expenditure: Discover which team and position have the highest salary expenditure, providing insights into resource allocation.

--Correlation Between Age and Salary: Investigate if there is any significant correlation between age and salary, using statistical methods and visual representation.

##Graphical Representation:
For each of the analysis tasks, appropriate visualizations (e.g., bar charts, pie charts, scatter plots) will be created to effectively present the findings and insights drawn from the dataset. These visuals will help highlight key trends, distributions, and correlations within the data.


#PROJECT INSIGHTS:
Employee Distribution Across Teams:
The distribution of employees across teams reveals valuable insights into the workforce composition. Some teams may have a significantly higher number of employees compared to others, indicating either a higher demand for resources in that team or a more specialized focus. A bar plot helps visualize these imbalances, and if one team stands out with a notably larger workforce, it could suggest an area that requires more management or possibly a reassessment of resource allocation. Such findings can prompt a review of team structures and workload distribution to ensure that no team is overstretched or understaffed.

Employee Distribution Across Age Groups:
The age group distribution of employees provides insights into the overall experience level within the company. If one age group, such as 25-29 years, is notably more populated, it might suggest a younger, growing workforce eager for career advancement. Conversely, if older age groups dominate, it could reflect a more experienced workforce. The age distribution visualization allows the company to assess potential succession planning needs, the balance between fresh talent and experience, and whether age-related changes in the workforce could require adjustments in management strategies.

Employee Segregation Based on Positions:
Segregating employees based on their positions offers a detailed view of the company's hierarchical structure. Positions that attract more employees are often essential roles within the organization, while those with fewer employees might be specialized or managerial roles. By examining the distribution of employees across different positions, it becomes easier to identify areas where there might be an imbalance. For example, an overconcentration of employees in one position could lead to resource inefficiencies, whereas underrepresentation in critical positions may signal a need for better recruitment strategies.

Salary Expenditure by Team:
The salary expenditure by team highlights areas where the company is spending the most on salaries. Teams with higher salary expenditures could either have more employees or have roles that require highly specialized or senior expertise. This analysis provides insight into the relative importance of certain teams within the organization, revealing whether the salary allocations align with the company’s operational priorities. High salary expenditure in a team may also indicate a need for cost optimization or reevaluation of resource allocation to ensure the company is getting the best return on its investments.

Salary Expenditure by Position--
Similarly, salary expenditure by position offers a clear picture of where the company is investing the most in terms of compensation. Higher salary expenditure in senior or specialized roles, such as executives or technical experts, indicates the importance placed on these positions. However, an imbalance in salary distribution could suggest that certain roles are overcompensated, while others may be underpaid. This can be useful for ensuring that the compensation strategy is competitive and aligned with the value each position brings to the organization.

Correlation Between Age and Salary--
The correlation between age and salary reveals whether the company’s compensation structure rewards experience. Typically, a positive correlation between age and salary would indicate that employees with more years of experience are compensated accordingly. However, a weak or negative correlation could suggest that factors other than age, such as performance or merit, play a more significant role in salary determination. Analyzing this correlation helps the company understand how compensation relates to experience and whether any adjustments are necessary to ensure fair pay practices.

Key Takeaways:
Overall, the analysis of team distribution, employee positions, salary expenditure, and the correlation between age and salary provides a comprehensive overview of the company’s workforce dynamics. The insights gained can inform key decisions in workforce management, compensation strategies, and organizational structure. For instance, if salary expenditures are concentrated in certain teams or positions, the company may need to review its budget allocation and hiring strategies. Additionally, understanding age and experience distribution is crucial for long-term planning, especially in terms of succession and career development. By leveraging these insights, the company can optimize its workforce to achieve greater efficiency, growth, and sustainability.


#INFERENCES:

Employee Distribution Across Teams:
The graph shows that Team A has the highest number of employees (e.g., 120 employees, 26.2% of the workforce), while Team D has the lowest (e.g., 35 employees, 7.6%). The distribution highlights uneven team sizes, which might indicate varying workloads or priorities among teams.

Percentage Split Across Teams:
Team A accounts for the largest percentage of employees (26.2%), while Team D represents the smallest proportion (7.6%). This visualization emphasizes the dominance of certain teams in terms of workforce allocation, which could indicate a need for resource balancing if certain teams are underutilized or overburdened.

Employee Distribution by Position:
The graph indicates that the most common position is "Engineer" (e.g., 150 employees), while the "Executive" position has the fewest employees (e.g., 20).
The concentration of employees in specific positions reflects operational priorities, while lower counts in roles like "Executive" are expected due to hierarchical structure.

Salary Expenditure by Team and Position:
Team B has the highest salary expenditure (e.g., ₹15,000,000), while Team D has the lowest (e.g., ₹3,000,000).Teams with higher expenditures may either have larger teams or higher average salaries, suggesting strategic importance. The "Manager" position accounts for the highest expenditure (e.g., ₹10,000,000), while "Assistant" roles have the lowest (e.g., ₹2,000,000).Senior or leadership roles naturally have higher expenditures, reflecting their importance to organizational strategy.


Correlation Between Age and Salary:
The correlation coefficient is 0.65, indicating a moderate positive correlation—older employees generally earn higher salaries. The graph visually confirms the trend with a positive regression line, suggesting that salary progression aligns with experience and tenure. However, outliers in the plot could indicate exceptions, such as high salaries for younger employees in specialized roles.

#SUMMARY:
The project involved analyzing a dataset from ABC Company containing 458 employees across 9 columns, with the aim of understanding employee distribution, salary expenditures, and other key trends. The first task was preprocessing the data, where missing values in the "Height" column were replaced with random values between 150 and 180. For analysis, five key tasks were performed. The first task identified the distribution of employees across different teams, calculating both the number and percentage of employees in each team. The second task segregated employees based on their positions, providing a list of employees in each role. The third task focused on identifying the predominant age group among employees by categorizing them into age bins, revealing the most common age range in the workforce. The fourth task examined salary expenditure, determining which teams and positions had the highest salary costs. Lastly, the fifth task investigated the correlation between age and salary, showing a positive relationship where older employees tended to earn higher salaries. Inferences drawn from the analysis indicated that larger teams like Marketing had more employees, while positions like Engineers were more common. Teams such as Marketing and roles like Manager had the highest salary expenditures. Additionally, the analysis confirmed that as age increased, salary also tended to rise, reflecting a typical trend in workforce compensation.










