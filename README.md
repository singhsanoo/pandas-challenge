# Summary
We created and manipulated Pandas DataFrames to analyze school and standardized (math & reading)test data. Few of trends and finding that became obivous are as follow:

1. Only 66% students from Dristrict school managed to pass Math test, where as 93% students from Charter School managed to pass Math test. 
2. On an average about 90% of the students from Charter Schools were able to score passing grades on both the test, in comparison with the students from District School where only about 53% students could mange to pass both test.
3. More students goes to District schools and Larger school size also shows lower over-all passing average, even though the funds per student is not widely spread out. The reason for bad performance could be low teacher to student ratio.  


## Background

Every student's math and reading scores, school informations are provided in [schools_complete](PyCitySchools/Resources/schools_complete) and [students_complete](PyCitySchools/Resources/students_complete) files, as well as various information on the schools budgets. 
This [script](PyCitySchools/PyCitySchools_starter.ipynb) aggregate the data to showcase obvious trends in school performance.

## Instructions

### District Summary

Creates a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary

Creates a DataFrame that summarizes key metrics about each school, including the following:

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

### Highest-Performing Schools (by % Overall Passing)

Creates a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:

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


### Lowest-Performing Schools (by % Overall Passing)

Creates a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:

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

### Math Scores by Grade

Creates a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade

Creates a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending

Creates a table that breaks down school performance based on average spending ranges (per student). By judgment four bins with reasonable cutoff values are choosen to group school spending. Following metrics are included in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size

Creates a table that breaks down school performance based on school size (small, medium, or large).
### Scores by School Type

Creates a table that breaks down school performance based on type of school (district or charter).

