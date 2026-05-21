# pr-3-gr-13184
Student Data Organizer
Project Description
The Student Data Organizer is a menu-driven Python application developed to manage student records efficiently using Python collection data types.
This project demonstrates the practical use of:
Lists
Sets
Tuples
Dictionaries
Functions
Loops
Conditional Statements
Type Casting
String Formatting
del Keyword
The program allows users to add, update, search, display, and delete student records through an interactive console menu.
Objectives
The main objectives of this project are:
To understand Python collection data types
To implement menu-driven programming
To perform CRUD operations using Python
To manage student records efficiently
To apply real-world data handling concepts
Features
1. Add Student
Allows the user to:
Enter Student ID
Enter Name
Enter Age
Enter Grade
Enter Date of Birth
Enter Subjects
The student data is stored in a dictionary inside a list.
2. Display All Students
Displays all student records in a formatted structure.
3. Update Student Details
Allows updating:
Student Name
Student Age
Student Grade
Student Subjects
4. Delete Student Record
Deletes a student using Student ID.
5. Display Unique Subjects
Displays all unique subjects stored in the set.
6. Search Student
Searches a student using Student ID.
7. Exit Program
Safely terminates the application.
Technologies Used
Technology
Purpose
Python
Programming Language
VS Code / PyCharm
Code Editor
Terminal
Program Execution
Python Concepts Used
Concept
Description
List
Stores all student records
Dictionary
Stores student details
Tuple
Stores immutable student information
Set
Stores unique subjects
Functions
Organizes program into modules
Loops
Repeats menu system
Conditional Statements
Decision making
Type Casting
Converts input values
String Formatting
Better output display
del Keyword
Deletes student records
Data Structures Used
List
Used to store multiple student records.
Example:
Python
student_records = []
Dictionary
Used to store student details.
Example:
Python
student_dictionary = {
    "name": "Krisha",
    "age": 19
}
Tuple
Used to store immutable student data.
Example:
Python
immutable_data = (student_id, dob)
Set
Used to store unique subjects.
Example:
Python
unique_subjects = {"Python", "Maths", "AI"}
Functions Used
Function Name
Purpose
add_student()
Adds new student
display_students()
Displays all students
update_student()
Updates student details
delete_student()
Deletes student record
display_unique_subjects()
Displays unique subjects
search_student()
Searches student
Program Flow
Program starts
Main menu is displayed
User selects an option
Corresponding function executes
Program returns to main menu
Repeats until Exit option is selected
How To Run The Program
Step 1
Install Python on your system.
Step 2
Save the file as:
Bash
student_data_organizer.py
Step 3
Open terminal or command prompt.
Step 4
Run the program using:
Bash
python student_data_organizer.py
Sample Menu Output
Plain text
====================================
              MAIN MENU
====================================

1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects Offered
6. Search Student
7. Exit
Advantages Of The Project
Beginner-friendly
Easy to understand
Real-world implementation
Good practical project
Demonstrates Python collections clearly
Useful for college submission
Future Improvements
The project can be enhanced by adding:
File Handling
Database Connectivity
Login System
GUI using Tkinter
Attendance Management
Marks Management
Export Data to Excel
Student Report Generation
Conclusion
The Student Data Organizer project successfully demonstrates the implementation of Python collection data types and menu-driven programming concepts. The project helps in understanding how data can be stored, managed, updated, searched, and deleted efficiently using Python.
Author
Developed Using Python
Mini Project – Collection Manipulator
Student Data Management System
