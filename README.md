<h1>Employee Attrition Analysis</h1>
<h3>Project Overview:</h3>
<p>In this project, I utilized Power BI to conduct a comprehensive analysis of employee turnover across various departments. I began by performing data transformation, where I cleaned the dataset by removing inconsistent and faulty data to ensure accuracy. I also added new columns where I categorized widespread data values from important columns.
My primary objective was to identify the key factors contributing to employee attrition and uncover patterns and trends in turnover. Through various data transformation operations, I gained a broader view of the data, making it easier to detect trends and extract meaningful insights.
The Power BI dashboard I created provided a comparative view of the data, enabling me to analyze it from multiple perspectives. Using Drillthrough-filters, I could dive deep into specific departments and extract valuable insights that helped to have a better interpretation of employee turnover dynamics.
</p>
<h3>Data Source:</h3>
<p>For this project, I utilized a CSV file downloaded from Kaggle.</p>
<p><b>Extended Employee Performance and Productivity Data:</b> It contained data of over 1 lakh employees along with details like Age, Gender, Department, Job title, Years at company, Performance score, Satisfaction score etc.</p>
<h3>Tool Used:</h3>
<ul>
  <li>Power BI Desktop</li>
  <li>Power BI Query Editor</li>
</ul>
<h3>Data Cleaning and transformation:</h3>
<p>The dataset contained no null values, so no null handling operations were necessary. However, there were some faulty records that needed attention. For example, certain employees aged between 20 and 24 were listed as having 7 to 9 years of experience, which was inconsistent. I cleaned up such erroneous entries to ensure data accuracy.
Additionally, I created new columns to offer a more comprehensive perspective of the dataset. In these columns, I grouped continuous variables like 'Age', 'Years at Company' and 'Monthly Salary' into distinct categories. This categorization is crucial for simplifying widespread data values and uncovering meaningful insights from the data.
</p>
<h3>Key Metrics Used:</h3>
<ul>
  <li>Total Employees</li>
  <li>Attrition count</li>
  <li>Attrition rate</li>
  <li>Average Performance Score</li>
  <li>Average Satisfaction Score</li>
  <li>Average Salary</li>
</ul>
<h3>Key Insights:</h3>
<ul>
  <li>The Finance, HR, Legal, and Marketing departments show attrition rates higher than the company average.</li>
  <li>Employees in the 40-50 and 50-60 age groups exhibit higher turnover rates compared to other age brackets.</li>
  <li>Alarmingly, employees with performance scores of 3 and 4 are leaving at higher rates, which is concerning for overall team performance.</li>
  <li>High attrition among top performers is most noticeable in the Finance, HR, Sales, and Operations departments.</li>
  <li>In terms of experience, the highest turnover is observed among entry-level employees (0-1 years), senior employees (8-9 years), and those with mid-level experience (6-7 years).</li>
  <li>The departments seeing high attrition of experienced and senior employees (6-9 years of experience) include Customer Support, Finance, Marketing, HR, and Sales.</li>
  <li>Entry-level and junior employees (0-3 years of experience) are primarily leaving from the Legal, Marketing, HR, and Finance departments.</li>
  <li>Gender-wise, most departments have similar attrition rates, with a few exceptions: female employees in Finance and IT have higher turnover, while in Legal and Marketing, males show slightly higher attrition than females.</li>
</ul>
<h3>In depth Analysis of high attrition departments:</h3>
<ol>
  <li>
    Finance:
    <ul>
      <li><b>High attrition among employees with two promotions:</b> Employees who received two promotions tend to leave at a higher rate. However, this trend is the opposite for both entry-level and more experienced employees, who show lower attrition rates.</li>
      <li><b>Attrition among high performers:</b> Junior and senior employees make up the majority of high-performing employees leaving the organization.</li>
      <li><b>Key factors driving high performers to leave:</b> Long working hours, excessive overtime, and low salaries contribute to the attrition of top performers. For senior employees, below-average salary is the most significant factor, whereas for junior employees, overtime, long working hours, and remote work frequency are the primary reasons.</li>
    </ul>
  </li>
  <li>
    HR:
    <ul>
      <li>High performers with two promotions are leaving at a faster rate.</li>
      <li>High attrition rates are prevalent among Junior, Mid-level, and Experienced employees.</li>
      <li>Among high performers, Experienced and Junior employees exhibit the highest attrition. Employees earning below 5k, which is significantly below average, are departing rapidly. For those with competitive salaries, factors like working hours, overtime, and the frequency of remote work are critical contributors to their decision to leave.</li>
      <li>Salary plays a significant role in the attrition of Junior and Mid-level employees.</li>
    </ul>
  </li>
  <li>
    Marketing:
    <ul>
      <li>In the marketing department, attrition is notably high among low performers, particularly at the Entry-level and Senior positions.</li>
      <li>For Entry-level employees, below-average salary is a key driver of attrition. While salary also impacts Senior employees, additional factors like overtime and long working hours significantly contribute to their decision to leave.</li>
      <li>Small team sizes are contributing to high attrition rates among Entry-level employees.</li>
    </ul>
  </li>
  <li>
    Sales:
    <ul>
      <li>In the Sales department, attrition is particularly pronounced among high performers, with Senior, Experienced, and Entry-level employees leaving at the highest rates.</li>
      <li>The factors influencing attrition vary by experience level. For Entry-level employees, those who have received two promotions tend to have low satisfaction scores and high attrition rates. Overtime and long working hours are also important factors.</li>
      <li>For Experienced employees, the frequency of remote work, overtime, and long working hours play a critical role in attrition.</li>
      <li>Senior employees with zero promotions are showing high attrition rates. The specific reasons for this are unclear, but attrition is especially high in the 20-30 and 40-50 age groups.</li>
    </ul>
  </li>
  <li>
    Legal:
    <ul>
      <li>The Legal department has the highest attrition rate among Entry-level employees.</li>
      <li>Entry-level employees in the 50-60 age group are leaving at an elevated rate, especially those earning between $5k and $7k, and those who have received two promotions.</li>
      <li>Overtime and long working hours are also major contributors to attrition, particularly for employees working 30-44 hours per week. This could be due to excessive overtime paired with below-expectation salaries. Employees with remote work frequencies of 50% and 100% are also leaving at high rates.</li>
      <li>A notable observation is that employees with two promotions show high attrition in two distinct age groups: 30-40 and 50-60. While salary does not appear to be a major factor for the 30-40 age group, it plays a crucial role for those aged 50-60.</li>
    </ul>
  </li>
</ol>
<h3>Learning Outcomes:</h3>
<p>This is my first Power BI project so it introduced me to various functions in Power BI like importing data in Power Query Editor, transforming and manipulating it there, and then loading it to Power BI desktop to create visuals. Creating a dynamic Power BI dashboard enhanced my ability to visually present data in a clear and interactive manner.
The project strengthened my analytical mindset, allowing me to approach complex problems, break down the data into manageable parts, and derive actionable insights. I also learned how to look at data from different angles to extract deeper meaning and implications.
</p>













