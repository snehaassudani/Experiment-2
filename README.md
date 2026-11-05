# Experiment-2

Aim:

To write a Python program that calculates the total and average marks of a student in five subjects and displays the corresponding grade using conditional statements. 

 Algorithm:

1. Start the program.
2. Display the heading "STUDENT GRADE CALCULATOR".
3. Initialize the variable total to 0.
4. Use a for loop to accept marks for five subjects.
5. Check whether the entered marks are between 0 and 100.
6. If the marks are invalid, display an error message and skip that iteration using the continue statement.
7. If the marks are valid, add them to the total.
8. Calculate the average by dividing the total marks by 5.
9. Display the total marks and average.
10. Use if-elif-else statements to assign a grade based on the average:
    - 90 and above – A+
    - 80 to 89 – A
    - 70 to 79 – B
    - 60 to 69 – C
    - 50 to 59 – D
    - Below 50 – F
11. Display the final grade.
12. Print "Program completed!".
13. Stop the program.

Output:

STUDENT GRADE CALCULATOR
Enter marks for subject 1: 80
Enter marks for subject 2: 30
Enter marks for subject 3: 90
Enter marks for subject 4: 50
Enter marks for subject 5: 60

Total Marks: 310
Average: 62.0
Grade: C
Program completed!
