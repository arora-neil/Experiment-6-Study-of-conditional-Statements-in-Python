# Aim: Study of conditional Statements in Python

# Theory: 
Conditional statements in Python are used for decision making in a program by executing different blocks of code based on whether a condition is true or false. 
These conditions are formed using comparison and logical operators. Python provides if, if–else, and if–elif–else statements to handle simple, alternative, and multiple condition checks. 
Conditional statements make programs more logical, readable, and useful in real-world applications such as validations, grading systems, and login checks.

# Algorithm:
i. Check wether the given number is postive, negative or zero.
 1. Start
 2. Read a number from the user
 3. If the number is equal to zero, display “Number is zero”
 4. Else if the number is greater than zero, display “Number is positive”
 5. Else, display “Number is negative”
 6. Stop

ii. Write a python program to check if given number is either even or odd.
 1. Start
 2. Read a number from the user
 3. Check if the number is divisible by 2
 4. If the remainder is zero, display “Number is Even”
 5. Otherwise, display “Number is Odd”
 6. Stop

iii. To find the largest number out of the given numbers
 1. Start
 2. Read three numbers a, b, and c from the user
 3. If a is greater than both b and c, display “a is largest”
 4. Else if b is greater than both a and c, display “b is largest”
 5. Else if c is greater than both a and b, display “c is largest”
 6. Otherwise, display “a, b, c are equal”
 7. Stop

iv. Get Input from user for 1 subject and calculate the grade using if-elif-else
 1. Start
 2. Read marks from the user
 3. If marks are greater than or equal to 90, display grade A
 4. Else if marks are greater than or equal to 75, display grade B
 5. Else if marks are greater than or equal to 60, display grade C
 6. Else if marks are greater than or equal to 40, display grade D
 7. Otherwise, display “Fail”
 8. Stop

v. Write python program to check if given year is leap year or not
 1. Start
 2. Read the year from the user
 3. If the year is divisible by 4 and not divisible by 100, or divisible by 400, display “Leap Year”
 4. Otherwise, display “Not Leap Year”
 5. Stop

vi. Write a program to increment the date
 1. Start
 2. Read the date from the user in dd/mm/yyyy format
 3. Extract day, month, and year from the input
 4. If the month has 31 days:
    If day < 31, increment day
    Else set day = 1 and increment month (or year if month is December)
5. Else if the month has 30 days:
   If day < 30, increment day
   Else set day = 1 and increment month
6. Else if the month is February:
   If the year is a leap year and day < 29, increment day
   Else if the year is not a leap year and day < 28, increment day
   Otherwise, set day = 1 and increment month
7. Display the new date
8. Stop
