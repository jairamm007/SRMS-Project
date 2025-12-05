# SRMS-Project
This C program implements a role-based student record management system where users (admin, staff, guest) can log in with credentials and access specific features. Depending on their role, users can view, add, update, search, or delete student information stored in a text file.

Student Report Management System(SRMS) (C Program)

A simple and efficient Student Management System written in C, featuring user authentication with role-based access control. The system stores student records and user credentials in text files, enabling easy usage without requiring a database.

Features:
User Login System-
Reads credentials from credentials.txt
Supports Admin, Staff, and Guest roles
Restricts access to functions based on user role

Admin Privileges-
Add new student records
Display all student records
Search for a student
Update student details
Delete a student record

Staff Privileges-
Add student
Display student list
Search student
Update student

Guest Privileges-
View student list
Search student

Functionalities:
Student Operations-
AddStudent() → Add roll, name, and marks
DisplayStudents() → List all student records
SearchStudent() → Search by roll number
UpdateStudent() → Modify existing record
DeleteStudent() → Remove a student entry

Role-Based Menus-
adminMenu()
staffMenu()
guestMenu()

Each menu limits features based on the logged-in role.
