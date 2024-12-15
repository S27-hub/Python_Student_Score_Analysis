# Python_Student_Score_Analysis
The project is done to understand the affects of the various parameters (like gender, parental education, marital status, and ethnic group etc) on student performance.

# Dataset source
Dataset of student scores has been taken from kaggle.

#  Importing the libraries 
For analysis importing the libraries is an essential step.
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

We can also import the libraries when we need them but importing the all libraries at once is a good practice.

# Loading the dataset and its overview
Dataset has been loaded and to get an overview of the data we call for the first five data with coloumns heading.
The dataset contains total of 15 coloumns named with one unnamed coloum, which we will drop to make our data more compact.
Data coloumns:
1. Gender: Gender of the student (male/female)
2. EthnicGroup: Ethnic group of the student (group A to E)
3. ParentEduc: Parent(s) education background (from some_highschool to master's degree)
4. LunchType: School lunch type (standard or free/reduced)
5. TestPrep: Test preparation course followed (completed or none)
6. ParentMaritalStatus: Parent(s) marital status (married/single/widowed/divorced)
7. PracticeSport: How often the student parctice sport (never/sometimes/regularly))
8. IsFirstChild: If the child is first child in the family or not (yes/no)
9. NrSiblings: Number of siblings the student has (0 to 7)
10. TransportMeans: Means of transport to school (schoolbus/private)
11. WklyStudyHours: Weekly self-study hours(less that 5hrs; between 5 and 10hrs; more than 10hrs)
12. MathScore: math test score(0-100)
13. ReadingScore: reading test score(0-100)
14. WritingScore: writing test score(0-100)
15. unnamed: 0

# Problem satatements
1. What factors affect test scores most?
2. Are there interacting features which affect test scores?

#  Data cleaning
The analysis begins with data cleaning to handle missing values and remove unnecessary columns. The "Unnamed: 0" column is dropped.

# Exploratory Data Analysis:
1. Visualizes the distribution of students by gender.
2. Analyzes the relationship between Parent's Education and students score.
3. Examines the correlation between parents' marital status and students scores.
4. Detecting the outliers in the Math, Reading and writing scores.
5. Visualiszing the distribution of different ethnic group using Pie Chart and Bar Graph.

# Observations
1. With the help of the graph we can obseve that the female students are more than male students
2. With the help of the heatmap we can state that the higher the education of the parents have higer impact on the marks of the students.
3. There is little to no effect of a parent's marital status on their childeren scores.
4. Box plot of all the three subjects indicates that there are outliers in all the subjects and the score in the math subject are the lowest as compared to the reading and writing scores of students.
5. A higher percentage of people belong to the Group C (i.e. 31.98%)


   



