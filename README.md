# Student Attendance Management System

## Project Overview

The **Student Attendance Management System** is a Python-based application developed as part of a **Software Configuration Management (SCM)** laboratory experiment. The primary objective of this project is to understand and implement Git for version control while developing a simple attendance management application.

The system provides basic functionalities for maintaining student records, recording attendance, generating attendance reports, calculating attendance percentages, and identifying students with low attendance. Throughout the project, Git is used to track every modification, maintain project history, restore deleted files, manage branches, and merge new features into the main project.

# Objectives

The objectives of this project are:

* To understand the concepts of Software Configuration Management (SCM).
* To learn the basic Git workflow.
* To create and manage a Git repository.
* To stage and commit project changes.
* To view repository status and project history.
* To restore accidentally deleted files using Git.
* To rename and remove files using Git commands.
* To implement feature development using Git branches.
* To merge feature branches into the main branch.
* To maintain proper project documentation.

# Functional Features

The Student Attendance Management System provides the following features:

* Add and maintain student records.
* Store course details.
* Record daily student attendance.
* Display attendance reports.
* Search students using Roll Number.
* Calculate attendance percentage automatically.
* Generate a list of defaulter students.
* Maintain project documentation.

# Non-Functional Features

* Developed using Python.
* Source code organized into separate modules.
* CSV files used for basic data storage.
* Git used for version control.
* Every important modification committed separately.
* Feature development performed using Git branches.

# Technologies Used

* Python
* Git
* Visual Studio Code
* CSV Files

# Project Modules

## app.py

Acts as the main application file. It displays the main menu and controls the execution of different modules.

## student.py

Handles all student-related operations such as storing student information and searching student records.

## attendance.py

Contains functions related to recording and maintaining student attendance.

## course.py

Stores and manages course information.

## report.py

Generates attendance reports for students.

## percentage.py

Calculates attendance percentage for each student.

## defaulter.py

Generates the list of students whose attendance is below the required percentage.

## database_manager.py

Performs reading and writing operations on CSV files.

## requirements.txt

Contains the project dependencies.

## README.md

Provides complete documentation of the project.

# Project Structure

```text
AttendanceManagementSystem/
│
├── app.py
├── student.py
├── attendance.py
├── course.py
├── report.py
├── percentage.py
├── defaulter.py
├── database_manager.py
├── requirements.txt
├── README.md
│
├── data/
│   ├── students.csv
│   ├── attendance.csv
│   └── courses.csv
│
└── screenshots/
```

# Git Workflow Followed

The following Git operations were performed during the development of the project:

1. Verified Git installation.
2. Configured Git username and email.
3. Created the project folder.
4. Initialized the Git repository.
5. Created the initial project structure.
6. Added all project files.
7. Created the first commit.
8. Added the Attendance Percentage module.
9. Added Student Search functionality.
10. Restored the deleted `attendance.py` file.
11. Renamed `database.py` to `database_manager.py`.
12. Removed the unused `utils.py` module.
13. Created the `defaulter-feature` branch.
14. Added the Defaulter List feature.
15. Merged the feature branch into the main branch.
16. Updated the project documentation.

# Expected Commit History

1. Initial project structure created
2. Added attendance percentage module
3. Added student search feature
4. Renamed database module
5. Removed unused utility module
6. Added defaulter list feature
7. Updated project documentation

# Future Enhancements

The project can be enhanced by adding the following features:

* Graphical User Interface (GUI)
* Database connectivity using MySQL or SQLite
* Faculty login authentication
* Automatic attendance using QR Code or RFID
* Email and SMS notifications for low attendance
* Student dashboard
* Report generation in PDF format
* Cloud-based data storage

# Conclusion

The Student Attendance Management System successfully demonstrates the practical implementation of Git in software development. Through this project, version control techniques such as repository initialization, staging, committing, restoring files, branching, merging, and maintaining project documentation were performed effectively. The project also illustrates how Git helps developers collaborate efficiently while maintaining the complete history of software development.


# Author

**Falak Sardar**
