# Santa Clara Workforce Ethnicity Analysis

<p>In this EDA, we are going to explore the county workforce dataset and trying to answer below questions:<br><br>
How does the entire workforce look like in ethnicity? Which ethnicity has a higher percentage?What about in different job category and departments?<br><br>
Are there any associations between enthinicity and job category or which department the workforce is in?<p>


  
Structures:
1. Get the datasource by calling the portal API
2. Explore the data and clean the data if necessary
3. Create plots
4. Use Chi-Square test for associations between categories
5. Conclusions
  <p>In the workforce: <br>

  * Almost 36% of the employees are Asian, 29% Hispanic and then followed by White employees, 24%.<br><br>
      <img src="./Top_3_employee_groups.png">

  
  * Among all the job categories, professionals, administrative support, protective service workers and technicians are the biggest groups. Asian employees dominiate professionals and Technicians job categories while, Hispanic employees dominate in job categories of Administrative Support and Protective Service Workers.<br><br>
      <img src="./Employee_count_in_job_category.png">


  * In all the departments, most of the Asian employees work in Santa Clara Valley Med Center, same as Hispanic and White employee. Compared with Asian and White employees, there is a higher percentage of Hispanic employees work in the social services agency.<br><br>
      <img src="./employee_count_in_department.png">

  * As the results of Chi-square test, both results are significant, meaning there are associations between ethnicity and job cateogry and department respectively. However since the categories may not be completely independent from each other which violates the assumptions, we can not draw the conclusions that the association is actually there. <p>
  
  
Laugange: Python <br>
Tools: Pandas, Numpy, Matplotlib.pyplot, Seaborn, Socrata <br><br>
<a href="https://data.sccgov.org/dataset/County-Workforce/tnhw-jtp5">Date Source</a> Last Updated atJanuary 21, 2021
