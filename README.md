# Student-grade-prediction-and-alcohol-consumption-

## Aim 

To find the most important features leading to alcohol consumption in students of secondary school and generating inference rules to predict the likeliness of a student to consume alcohol using a decision tree and to predict the final grade of a student. It simply aims at finding how drinking alcohol at this age affects the student's final grades.
 
 ## Objective
 
The objective is to find the factors and most important features which lead to students indulging in drinking and consuming alcohol and how it affects their final grades in school. After the exploratory data analysis a decision tree is trained and inference rules are generated to predict which student is most likely to consume alcohol and the final grades of students using the most relevant features extracted after analyzing the dataset.


## Decision tree obtained from one of the model

![Decision Tree](https://github.com/Architectshwet/Student-grade-prediction-and-alcohol-consumption-/blob/master/model.png)


In the above decision tree the leaf nodes are the final grades of the students out of 20.


## Attributes in the dataset

The data were obtained in a survey of students maths course in secondary school.It contains a lot of interesting social, gender and study information about students.


Attributes for student-mat.csv (Math course) :

school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)

sex - student's sex (binary: 'F' - female or 'M' - male)

age - student's age (numeric: from 15 to 22)

address - student's home address type (binary: 'U' - urban or 'R' - rural)

famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)

Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)

Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)

Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)

Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')

Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')

reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')

guardian - student's guardian (nominal: 'mother', 'father' or 'other')

traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)

studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)

failures - number of past class failures (numeric: n if 1<=n<3, else 4)

schoolsup - extra educational support (binary: yes or no)

famsup - family educational support (binary: yes or no)

paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)

activities - extra-curricular activities (binary: yes or no)

nursery - attended nursery school (binary: yes or no)

higher - wants to take higher education (binary: yes or no)

internet - Internet access at home (binary: yes or no)

romantic - with a romantic relationship (binary: yes or no)

famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)

freetime - free time after school (numeric: from 1 - very low to 5 - very high)

goout - going out with friends (numeric: from 1 - very low to 5 - very high)

Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)

Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)

health - current health status (numeric: from 1 - very bad to 5 - very good)

absences - number of school absences (numeric: from 0 to 93)


These grades are related with the course subject Maths:

G1 - first period grade (numeric: from 0 to 20)

G2 - second period grade (numeric: from 0 to 20)

G3 - final grade (numeric: from 0 to 20, output target)

# Some Analysis

MAJOR OBSERVARTION-

1) Majority of students have parents living together.

2) Maximum no of students study 2 to 5 hours weekly and least 10 hours weekly.

3) After checking the proportions of Pstatus and study time-we find out that for students 
whose parents are together they study more compared to those whose parents who do not live together.

4) More number of males participate in extra caricullar activities than females.

5) Most of the students chose the school with proper and appt courses offered by them and reputation 
   and closer to home as well.
   
6) More no of females went for schools's reputation than males.

7) Most of the students have internet connections at home.

8) Students-All students who are studious -> wants to pursue higher education.(usually who study 2-10 hours in a week)

9) In both rural and Urban areas Females are more studious and hard working.

10) In rural areas 6% said No for higher edu and rest 93% students from RURAL areas said YES for Higher EDU out of total population in RURAL area.

11) In URABN area 4 % for the Students said NO and rest 95 % Students said YEs for higher EDU out of total population in URBAN area.

12) More mothers went for higher education(4) than Fathers of the students in the sample.

13) Family Support in Education and their effect on the children and their Study Habits






