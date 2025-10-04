# 🤓 Interactive Lesson 2 - School Data Science

## Topics Covered

- Using key **data structures** to manipulate and store information in efficient ways (dictionary, tuple, and sets)
- Using NumPy and Pandas to do some introductory data analysis

## Assignment Instructions
You are tasked with parsing a set of student statistics and calculating relevant information provided to you by a school administrator. The school wants you to read a CSV file of studnet names, grade levels, assignments, and assignment scores. You are to group together information by student name, by grade level, and by assignment. For each grouping, calculate the average score, the minimum score, and the maximum score. 
1) In analyze.py, write code that reads the student_info.csv file and stores it as a Pandas DataFrame.
2) Use one of the data structures we discussed to store that information in three groupings. One grouping should use student names as keys, one should use grade level as keys, and the third should use assignment as keys. All should map to assignment scores.
   - Hint: What's a data structure that can map keys, to values in Python?
   - Hint: If we are storing the assignment scores as values, and there could be multiple of them, what is the best way to represent this data? (Think of NumPy here!)

3) Generate a report for the students. For each student, show their average assignment score, their minimum assignment score, and their maximum assignment score. Use built-in NumPy functions to handle this.
4) Generate a report for the grade levels. For each grade level, show their average assignment score, their minimum assignment score, and their maximum assignment score. Use built-in NumPy functions to handle this
5) Generate a report for the assignment. For each assignment, show their average assignment score, their minimum assignment score, and their maximum assignment score. Use built-in NumPy functions to handle this
