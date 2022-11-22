<p align="center">
<h1 align="center">
<img src="https://github.com/theidari/pandas-challenge/blob/main/ban2.gif">
</h1>
</p>

<p align="center">
<sup><i> Pandas Challenge - UofT Data Analytics BootCamp</i></sup>
</P>

<p align="center">
<b> | ◰</b>
<a href="https://github.com/theidari/pandas-challenge#-overview-of-project">Overview of Project</a>
<b> | ◱</b>
<a href="https://github.com/theidari/pandas-challenge#-code">Code</a>
<b> | ◲</b>
<a href="https://github.com/theidari/pandas-challenge#-result">Results</a>
<b> | ◳</b>
<a href="https://github.com/theidari/pandas-challenge#-documents--references">Documents & References</a>
<b> |</b>
</P>

<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Emergency_Light.gif" width="30">
<b>Please let me know your <a href="https://docs.google.com/forms/d/e/1FAIpQLSeGzjpBarW10Wo8ApcSHtgchsMPmnSEgx5qDBnDGbkV1wQwDQ/viewform?usp=sf_link">feedback</a> Tnx<i>!</i></b>
</P>




## ◰ Overview of Project

This project used python programming language and jupyter notebook to analyze school budgets and priorities and report school performance to the school board and mayor for making strategic decisions based on math and reading scores.

### Objective:


<table align="center" border="0.1px" bordercolor = "white"
<tr>
<td >
<table>
<tr> 
<td>

<table border="2px" bordercolor="#F35557">
<h4 align="center"><b>⓵ District Summary</b></h4>
<tr>
<td>
    Create a dataframe to hold:</br>
      - total number of schools</br>
      - the total number of students</br>
      - total budget</br>
      - average math score</br>
      - average reading score</br>
      - passing math score percentage (70 or greater)</br>
      - passing reading score percentage (70 or greater)</br>
      - passing math and reading percentage (% Overall Passing)</br>
      </br>
      </br>
</td>
</tr>
</table>

</td>
<td>

<table border="2px" bordercolor="#F35557">
<h4 align="center"><b>⓶ School Summary</b></h4>
<tr>
<td>
    Create a dataframe to hold:</br>
        - School Name</br>
        - School Type</br>
        - Total Students</br>
        - Total School Budget</br>
        - Per Student Budget</br>
        - Average Math Score</br>
        - Average Reading Score</br>
        - % Passing Math</br>
        - % Passing Reading</br>
        - % Overall Passing</br>
</td>
</tr>
</table>



</td> </tr>
</table>
</td>
</tr>
<tr>
<td>

<table border="2px" bordercolor="#F35557">
<h4 align="center"><b>⓷ School Performance</b></h4>
<tr>
<td>
        - top five (% overall passing)</br>
        - top five (% overall passing)</br>
        - table that lists the average Math Score for students grade (9th, 10th, 11th, 12th) at each school</br>
        - table that lists the average reading Score for students grade (9th, 10th, 11th, 12th) at each school</br>
        - Score by Spending Ranges (Per Student) / School Size / School Type, include:</br>
            * Average Math Score</br>
            * Average Reading Score</br>
            * % Passing Math</br>
            * % Passing Reading</br>
            * Overall Passing Rate</br>
</td>
</tr>
</table>
</td>

</tr>
</table>






### Methods and Software:</br>
  - The analyses were performed using the <a href="https://github.com/theidari/pandas-challenge/edit/main/README.md#resources">Resources</a> dataset.</br>
  - Following Software and programming language were used in this project:
    * <b>jupyter notebook v.6.4.12</b>
    * <b>Visual Studio v.1.73.1</b>
    * <b>pandas v.1.4.4</b>
    * <b>python v.3.9.13</b>

## ◱ Code

<a href="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Main.ipynb">Code</a>

<p align="right">
<a href="https://github.com/theidari/pandas-challenge#-overview-of-project"><sup><b>⬆ BACK TO TOP ⬆</b></sup></a>
</P>

## ◲ Result
### District Summary
The results of 15 schools show that: The total amount of budget is 24,649,428,00 $. and the percentage of overall passing is 65.17, Also passing reading course is easier than math by 85.81%.

> <sub>District Summary</sub>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/District%20Summary.png">

### School Summary
Below table compares 15 schools e.g. type, total students, budget and etc.</br>

> <sub>School Summary</sub>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/School%20Summry.png">
After Sorting by % overall passing, it shows charter type schools outperform others with more than 90%. probably due to less number of students even though the budget per students are less than district type schools. also in charter schools both math and reading course average are the same and they are uper than 80, but in district school they are not equal and student in this type schools have a weakness in math course with average of 77 and passing rate of 66 %.</br>

> <sub>School Summary Top Performing</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/Top%20Performing.png">

> <sub>School Summary Bottom Performing</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/Bottom%20Performing.png">

<p align="right">
<a href="https://github.com/theidari/pandas-challenge#-overview-of-project"><sup><b>⬆ BACK TO TOP ⬆</b></sup></a>
</P>

### Math / Reading Score by Grade
According to the following tables, Math scores are averagely less than the reading scores across schools. Moreover, the math score decreases as the grade increases. However, this pattern is not observable for reading scores. 

<table align="center" border="0.1px" bordercolor="#8707B0">
<tr>
<td>

> <sub>Math Score by Grade</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/Math%20Score%20by%20Grade.png" width="350">

</td>
<td>

> <sub>Reading Score by Grade</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/Reading%20Score%20by%20Grade.png" width="350">

</td>
</tr>
</table>

### Score by School Spending
Results indicate that by increasing Spending the money per student, the Overall average and overall percent decreases across all schools.</br>
> <sub>Score by School Spending</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/Spending%20Ranges%20(Per%20Student).png">

### Score by School Size
Results indicate that increasing the number of students up to 2000 does not affect the students results,but the schools with more than 2000 students significantly affect the performance.</br>
> <sub>Score by School Size</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/School%20Size.png">

### Score by School Type
Charter schools with an overall passing of >90% significantly outperform District schools with an average of 53%.</br>
> <sub>Score by School Type</sub></br>
<img src="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Results%20Images/School%20Type.png">

### Conclusions

1. Charter schools overall are significantly better than District schools.</br>
2. Spending more money does not increase students’ performance in courses.</br>
3. It is highly recommended that keep capacity of schools be lower than 2000 students.</br>


<p align="right">
<a href="https://github.com/theidari/pandas-challenge#-overview-of-project"><sup><b>⬆ BACK TO TOP ⬆</b></sup></a>
</P> 

## ◳ Documents & References

### Documents:</br>

<table align="center" table border="1px" bordercolor="b">
<tr>
<td>
<table border="2px" bordercolor="#F35557">
<h4 align="center"><b><ins>Resources</ins></b></h4>
<tr>
<td><a href="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Resources/schools_complete.csv">Schools Data</a></td>
<td><a href="https://github.com/theidari/pandas-challenge/blob/main/PyCitySchools/Resources/students_complete.csv">Students Data</a></td>
</tr>
</table>
</td>
<td>
<table border="2px" bordercolor="#F35557">
<h4 align="center"><b><ins>Results</ins></b></h4>
<tr>
<td><a href="https://github.com/theidari/pandas-challenge/tree/main/PyCitySchools/Results%20Images">Images</a></td>
</tr>
</table>
</td>
</tr>
</table>


### References:</br>
<sup>[1]</sup> Data generated by [Mockaroo, LLC](https://mockaroo.com/), (2022). Realistic Data Generator.</br>
<sup>[2]</sup> Trilogy Education Services, a [2U, Inc.](https://2u.com/) brand.


<p align="right">
<a href="https://github.com/theidari/pandas-challenge#-overview-of-project"><sup><b>⬆ BACK TO TOP ⬆</b></sup></a>
</P>
