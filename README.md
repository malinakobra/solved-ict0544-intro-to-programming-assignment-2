Download Link: https://assignmentchef.com/product/solved-ict0544-intro-to-programming-assignment-2
<br>
QUESTION:

A course registration system is offering several courses under the Arts and Sciences categories. A student is allowed to choose and register a number of courses (max is six) and the system will count the number of courses in each category.

Write a C program to check for a valid matric number that contains six digits. Display appropriate message if the matric number is invalid.

The system will display all courses with their codes as follows:

A – Accounting B – Business C – ComputingE – Engineering M – Medicine P – Pharmacy

Then, request a user to enter the number of courses and the codes of selected courses. If a user enters the wrong code, the program will display a warning message “Invalid Code!”. The program will count and display the number of courses registered under the Art and Science categories. (Note: All courses are under Science category except for Accounting and Business)

The program should:1. print list of courses,2. get the number of courses taken, and3. get the codes, to count the number of courses under each category, and to display the number of registered Art and Science courses for that student.The system also calculates total credit hours for the courses registered (credit hour for Art subject is four and Science subject is five).A student may decide to reset or submit the registration data (number of courses and course codes).

Sample output:

Welcome to Course Registration System

Input your 6-digit matric number: 12318Not enough digitsInput your 6-digit matric number: 1231873Too many digitsInput your 6-digit matric number: 123187

A – Accounting B – Business C – ComputingE – Engineering M – Medicine P – Pharmacy

Please enter number of courses to be taken: 3Enter your course code: AEnter your course code: ZInvalid Code!Enter your course code: AYou have registered this course. Try another course.Enter your course code: EEnter your course code: M

Would you like to reset OR submit this course registration?(1-Reset 2-Submit): 2

123187, you have registered 1 Art course(s) and 2 Science course(s). Total credit hours is 14.

Thank you for using this system.


