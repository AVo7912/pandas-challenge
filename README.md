# pandas-challenge
 Week 4 HW
 
Analysis Summary

The city's school district of 15 schools and 39,170 students has a total budget of $24,649,428.00. The analysis includes information such as results of standardized test results in math and reading and budget per student. The data is used to measure performance among the schools and provides insights on budgeting. Schools are compared by type, budget, tests scores, and passing rates. Additional analysis includes comparison in performance between grade levels at each school, spending ranges, size, and type comparisons to test score averages and pass rates.

Conclusions:

1. When comparing Charter schools to District schools, Charter schools outperformed District schools in math, reading, and passing rate. The top 5 performing schools were all charter schools. The overall passing rate was the most significant different between the two types of schools with a difference of -36.760035.

 <div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Average Math Score</th>
      <th>Average Reading Score</th>
      <th>% Passing Math</th>
      <th>% Passing Reading</th>
      <th>% Overall Passing</th>
    </tr>
    <tr>
      <th>School Type</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Charter</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>District</th>
      <td>-6.517119</td>
      <td>-2.929784</td>
      <td>-27.072377</td>
      <td>-15.787427</td>
      <td>-36.760035</td>
    </tr>
  </tbody>
</table>
</div>

2. In regards to budget per student, there was not a significant difference between each school's budget per student. Even though schools varied in size and type, they were allocated a similar amount in relation to their school size. There was only a $77 difference from the highest budget per student to the lowest budget per student. Even though schools had similar budgets, performance varied. The Wilson High School had the lowest budget per student ($578) but was the 4th top performing school. In contrast, Huang High School had the highest budget per student ($655) but was the 3rd lowest performing school. In the spending range analysis, schools that had the lowest spending range performed better than schools with the highest spending range.

<div>

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Per Student Budget Mean</th>
      <th>Per Student Budget Median</th>
      <th>Highest Per Student Budget</th>
      <th>Lowest Per Student Budget</th>
      <th>Per Student Budget Difference</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>620.066667</td>
      <td>628.0</td>
      <td>655.0</td>
      <td>578.0</td>
      <td>77.0</td>
    </tr>
  </tbody>
</table>
</div>
