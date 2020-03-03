# Pandas_Challenge
Homework04_DS Bootcamp

Repository includes:
This README file with description of contents and homework instructions
PyCitySchools folder containing:
  Resources folder:
    schools_complete.csv file
    students_complete.csv file
  .jpynb_checkpoints folder -- saved checkpoints when coding
  PyCitySchools.jpynb -- contains code for the homework04 Pandas Challenge


# Observable trends based on the data generated:
    # Charter schools have a strikingly better overall passing rate compared to District schools (95% vs 74%, respectively)
    # However, the Charter schools do not perform better based on overall passing rate when looking at funding per student.
        #In fact, suprisingly, there appears to be an inverse relationship between amount of funding per student and their
        # overall passing rate.  This is most evident in math passing scores, where ~94% of students pass math when spending
        # per student is <$615.  In comparison, when spending per student is >$645, the math passing rate drops dramatically
        # to 66%. Is there a correlation with the number of available computers/calculators and math passing rate?
    #Small to medium schools have a better overall passing rate compared to larger schools (2000-5000 students).
        # Could this be a direct result of a better teacher to student ratio?  No teacher data was given, so it is unknown

From homework instructions:
Your final report should include each of the following:

District Summary
Create a high level snapshot (in table form) of the district's key metrics, including:
Total Schools
Total Students
Total Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

School Summary
Create an overview table that summarizes key metrics about each school, including:
School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

Top Performing Schools (By Passing Rate)
Create a table that highlights the top 5 performing schools based on Overall Passing Rate. Include:
School Name
School Type
Total Students
Total School Budget
Per Student Budget
Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

Bottom Performing Schools (By Passing Rate)
Create a table that highlights the bottom 5 performing schools based on Overall Passing Rate. Include all of the same metrics as above.

Math Scores by Grade**
Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:

Average Math Score
Average Reading Score
% Passing Math
% Passing Reading
Overall Passing Rate (Average of the above two)

Scores by School Size
Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

Scores by School Type
Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).
