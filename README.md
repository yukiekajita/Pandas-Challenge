# Pandas-Challenge: PyCitySchools Data Analysis Using Python Pandas

I analyzed the district-wide standardized test results. I was given access to every student's math and reading scores, as well as various information on the schools they attend. My responsibility was to aggregate the data to and showcase obvious trends in school performance.

My final report included each of the following:

### District Summary

* Created a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  ![image1](PyCitySchools/images/3.png)

### School Summary

* Created an overview table that summarized key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  ![image2](PyCitySchools/images/4.png)

### Top Performing Schools (By % Overall Passing)

* Created a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  ![image1](PyCitySchools/images/top.png)

### Bottom Performing Schools (By % Overall Passing)

* Created a table that highlighted the bottom 5 performing schools based on % Overall Passing. Included all of the same metrics as above.

  ![image1](PyCitySchools/images/6.png)

### Math Scores by Grade

* Created a table that listed the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

  ![image1](PyCitySchools/images/math.png)

### Reading Scores by Grade

* Created a table that lised the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

  ![image1](PyCitySchools/images/reading.png)

### Scores by School Spending

* Created a table that broke down school performances based on average Spending Ranges (Per Student). Used 4 reasonable bins to group school spending. Included in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)
  
  ![image1](PyCitySchools/images/7.png)

### Scores by School Size

* Repeated the above breakdown, but this time grouped schools based on a reasonable approximation of school size (Small, Medium, Large).

  ![image1](PyCitySchools/images/8.png)

### Scores by School Type

* Repeated the above breakdown, but this time grouped schools based on school type (Charter vs. District).

  ![image1](PyCitySchools/images/9.png)

  ![image1](PyCitySchools/images/10.png)
  
### Observation Note
* Charter schools had higher scores in Math and Reading, the percentages of Passing Math, Reading, and Overall Passing, comapred with the District Schools. Based on the percentage of overall passing, top 5 schools were all charter schools (i.e., ~90-91% in overall passing), and bottom 5 schools were all district schools (i.e., ~53% in overall passing). When I looked at the Math and Reading Scores in the different grade levels from 9th to 12th, I did not see any different tendencies in those greade levels. Charter schools had smaller size in the total number of students compared with the District Schools; therefore, the school size might explain why charter schools were doing better than District schools.

* Although District schools did not do well in Math, they had better scores and the percentage passing in Reading. The average Math score in the District Schools was 76.96, but the average Reading score was 80.97. The percentages of Passing Math was 66.55% and the percentage of Passing Reading was 80.79%. 
