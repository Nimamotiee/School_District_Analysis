# School_District_Analysis
## Overview of Project
  ### Here is the list of deliverables for the analysis of the school district:

  * A high-level snapshot of the district's key metrics, presented in a table format
  * An overview of the key metrics for each school, presented in a table format
  * Tables presenting each of the following metrics:
  * Top 5 and bottom 5 performing schools, based on the overall passing rate
  * The average math score received by students in each grade level at each school
  * The average reading score received by students in each grade level at each school
  * School performance based on the budget per student
  * School performance based on the school size
  * School performance based on the type of school Before we can begin these tasks, we need to import the datasets into Jupyter Notebook using Python.
  
  
  ## Results
  ### Before Data Manipulation:
  * Average Math Score = 79.0
  * Average Reading Score = 81.9
  * % Passing Math 75
  * % Passing Reading 86
  * % Overall Passing 65


  ### AFTER DATA CLEANUP

  * Average Math Score = 78.9
  * Average Reading Score = 81.9
  * % Passing Math 74.8
  * % Passing Reading 85.7
  * % Overall Passing 64.9

  ### OBSERVATION: Given the changes there was a slight change in overall Math Scores, including % passing district avg. Comparing the two DFs above, the avgs show the differences when the 9th grade students scores from THS were excluded.

### How is the school summary affected?

  # Before Data Manipulaton:

  * Thomas High School's % Overall Passing was 91, placing second

  # Afer Data Manipulation:
  * Thomas High School's % Overall Passing was 65, placing eight
  
### Observation: Overall order change due to Thomas High School cleanup

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

#OBSERVATION: Replacing ninth graders’ math and reading scores affect Thomas High School’s performance between the other schools, Relative ranking for Thomas High School changed from 2nd place to 8th

### How does replacing the ninth-grade scores affect the following:
## Analysis Below:

## Math and reading scores by grade

* Math and Reading Scores from Thomas High School 9th Grade set to "nan" and equivalent to 0.
* Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
* Doing that, the only significantly score affected was minimal in a very small in quantity.
* Student count() Before THS Cleanup was: 1635
* Student count() After THS Cleanup was: 1174

* Scores by school spending

* Thomas HS is in the spending bucket "$630-644"
* Math and Reading Scores from Thomas High School 9th Grade means all of them failed (set to fail for analysis).
* Doing that, the only significantly score affected was minimal in a very small in quantity.
* Student count() Before THS Cleanup was: 1635
* Student count() After THS Cleanup was: 1174


* Scores by school size

* Removing Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for size bucket.
# In Addition

* Removing Students from Thomas High School 9th Grade reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644"
* Thomas High School is allocated on Spending Bin "$630-644"

* Scores by school type

* Thomas High School is in the "CHARTER" type
* Removing Thomas High School 9th Grade scores reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing", see below.

### 
Summary: Summarize the Average Math & Reading scores, % Passing Math and Reading scores, Overall Passing marks changes, changes that are reflected in the funding for each student (Difference each students funding is ~ $200).
