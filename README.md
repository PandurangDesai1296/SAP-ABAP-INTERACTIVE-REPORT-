# SAP-ABAP-INTERACTIVE-REPORT-
SAP ABAP INTERACTIVE REPORT  

🎓 SAP ABAP Interactive ALV Report – College Management System

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

📌 Project Overview : 

This project demonstrates an **Interactive ALV Report** developed in **SAP ABAP** for a College Management System. The report consolidates data from multiple custom database tables and displays comprehensive student, course, faculty, and enrollment information in a single ALV Grid.

The report utilizes **Interactive ALV functionality**, allowing users to click on specific fields and perform drill-down navigation actions.

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

🚀 Features

 Interactive ALV Grid Display
 Multi-table Data Retrieval using INNER JOIN and LEFT OUTER JOIN
 Student Information Display
 Course Details Display
 Faculty Information Display
 Enrollment Tracking
 Hotspot Functionality
 User Command Handling
 Reusable ALV Field Catalog Configuration

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

📂 Database Tables Used

 Student Master Table

ZSTUDENT_DATA

Fields:

Student ID
Name
Date of Birth
Gender
Email
Phone Number
Address

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

Course Master Table

ZCOURSE_DATA

Fields:

Course ID
Student ID
Course Name
Duration
Fees

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

Faculty Master Table

ZFACULTY_DATA

Fields:

Faculty ID
Course ID
Subject
Email

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

Enrollment Table

ZENROLLMENT_DATA

Fields:

Enrollment ID
Student ID
Course ID
Enrollment Date

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

🔧 ABAP Concepts Used

Reports
Classical Executable Report
Internal Tables
Standard Internal Tables
Structures
Custom Structure Definition
Open SQL
INNER JOIN
LEFT OUTER JOIN
WHERE Clause Filtering

ALV Reporting

REUSE_ALV_GRID_DISPLAY_LVC
LVC Field Catalog

Interactive Reporting

Hotspot Column
User Command Callback
Double Click Event Handling

Selection Screen

SELECT-OPTIONS

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>



📊 Report Output

The report displays:

| Student Information | Course Information | Faculty Information | Enrollment Information |
| ------------------- | ------------------ | ------------------- | ---------------------- |
| Student ID          | Course ID          | Faculty ID          | Enrollment ID          |
| Name                | Course Name        | Subject             | Enrollment Date        |
| DOB                 | Duration           | Faculty Email       |                        |
| Gender              | Fees               |                     |                        |
| Email               |                    |                     |                        |
| Phone               |                    |                     |                        |


<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

 🔄 Execution Flow

1. User enters Student ID on Selection Screen.
2. System fetches data from:

   * ZSTUDENT_DATA
   * ZCOURSE_DATA
   * ZFACULTY_DATA
   * ZENROLLMENT_DATA
3. Joined data is stored in an internal table.
4. Field Catalog is dynamically prepared.
5. ALV Grid is displayed.
6. User clicks on hotspot-enabled Student ID.
7. Callback routine handles the event.
8. Corresponding transaction is triggered.

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

🎯 Learning Objectives

This project helps understand:

* Interactive ALV Reporting
* ALV Grid Display Function Module
* Hotspot Handling
* User Command Processing
* Open SQL Joins
* Internal Table Processing
* Field Catalog Creation
* SAP ABAP Reporting Techniques

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

 🛠️ Technologies Used

* SAP ABAP
* Open SQL
* ALV Grid (LVC)
* Function Modules
* SAP GUI

<<<<--------------------------------------------------------------------------------------------------------------------------------->>>>

Focused on:

* Core ABAP Development
* Data Dictionary (DDIC)
* Reports
* ALV Reports
* Smart Forms
* Function Modules
* Modularization Techniques
* SAP S/4HANA ABAP Development



