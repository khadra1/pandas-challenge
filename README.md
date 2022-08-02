# pandas-challenge
## Manipulating Pandas DataFrames to analyse a particular city's school and standardised test data.


# PyCity Schools Analysis

I've analysed the district-wide standardised test results for a city's schools using Pandas Dataframes and Pyhton 3. The dataset used contains every student's math and reading scores, as well as various information on the schools they attend. I aggregated the data to showcase obvious trends in school performance.
![Screenshot 2022-08-02 at 14 36 54](https://user-images.githubusercontent.com/67019030/182388236-218e3e4f-293f-4103-8e49-5c3847e634bd.png)



# School Tests Data Analysis Report

### Observed trends: 

According to the results of **Scores by School Spending** and the **Scores by School Size**, the top performing schools have some of the lowest number of total students and some of lowest per student budget. Smaller schools with smaller per student budgets perform better in comparison with bigger schools with greater per student budgets.

Looking at the **Scores by School Type**, the 5 **Top Performing Schools** by Overall Passing % and the 5 **Bottom Performing Schools** by Overall Passing % , all 5 bottom schools are **District** schools, whereas all 5 top performing schools are **Charter** schools.

And lastly from the result on the **Reading and Math Scores by Grade**, the average reading grade fluctuates at around 1% difference between the 9th-12th grade in all schools. When comparing schools against each other there is a bigger variance than comparing different grades in the same schools which seems to be consistent in all schools.



# Steps Taken:

### District Summary

A DataFrame that summarizes key metrics about each school district. With the following metrics:
* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

![Screenshot 2022-08-02 at 14 40 29](https://user-images.githubusercontent.com/67019030/182388975-d8e39df7-91f7-449e-9536-9f7d58123444.png)



### School Summary

A DataFrame that summarizes key metrics about each school. With the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

![Screenshot 2022-08-02 at 14 41 24](https://user-images.githubusercontent.com/67019030/182389356-8d39a21f-a9d5-406f-ba3a-26cf448083bc.png)




### Highest-Performing Schools (by % Overall Passing)

A DataFrame that highlights the top 5 performing schools based on % Overall Passing. With the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)
![Screenshot 2022-08-02 at 14 49 28](https://user-images.githubusercontent.com/67019030/182390952-4b62bb8a-b6f2-4d4a-a8b5-94b586487291.png)




### Lowest-Performing Schools (by % Overall Passing)

A DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. With the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)
![Screenshot 2022-08-02 at 14 50 52](https://user-images.githubusercontent.com/67019030/182394249-75e3cc6f-8b8f-4417-8fa3-129c6b12f4cf.png)



### Math and Reading Scores by Grade
DataFrames that list the average math and the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
<table>
  <tr>
    <td>Math Scores By Grade Level</td>
     <td>Reading Scores by Grade Level</td>
  </tr>
  <tr>
    <td><img src="PyCitySchools/images/math_by_grade.png" width=500 height=480></td>
    <td><img src="PyCitySchools/images/reading_by_grade.png" width=500 height=480></td>
  </tr>
 </table>

### Scores by School Spending
School performance based on average spending ranges (per student). I created four bins with reasonable cutoff values to group school spending. With the following metrics:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)
![Screenshot 2022-08-02 at 15 32 00](https://user-images.githubusercontent.com/67019030/182400149-2d460df9-7f05-42c1-8502-69b3d4b405f5.png)

### Scores by School Size
School performance based on school size (small, medium, or large).
![Screenshot 2022-08-02 at 15 33 35](https://user-images.githubusercontent.com/67019030/182400847-7137a37e-6c2e-434b-9e5f-135cadc12b0e.png)

### Scores by School Type
School performance based on type of school (district or charter).
![Screenshot 2022-08-02 at 15 34 24](https://user-images.githubusercontent.com/67019030/182400825-0d8ad6c7-d266-4813-a1e5-2b98a2eae2a6.png)

