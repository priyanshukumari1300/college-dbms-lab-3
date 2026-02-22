College Database System – DBMS Lab Assignment

**Introduction**

This project is a simple implementation of a College Database System using SQL.
It was created as part of a DBMS laboratory assignment to understand how relational databases store and manage structured data.

The system manages information related to departments, faculty members, courses, students, and their enrollments.

---

**Purpose of the Project**

The main goals of this lab are:

- To practice designing relational database tables
- To insert real-world structured data using SQL
- To understand relationships between entities
- To verify stored data using queries

---

**Database Structure**

The database consists of five main tables.

Department

Stores basic information about each department in the college.

Attributes:

- Department_ID
- Department_Name
- Office_Block

Faculty

Contains information about teachers working in departments.

Attributes:

- Faculty_ID
- Faculty_Name
- Designation
- Email
- Department_ID

**Course**

Represents the subjects offered by departments.

Attributes:

- Course_ID
- Course_Name
- Credits
- Department_ID
- Faculty_ID

**Student**

Stores student personal and academic details.

Attributes:

- Student_ID
- Student_Name
- Date_of_Birth
- Gender
- Contact_Number
- Department_ID

Enrollment

This table connects students with the courses they study.

Attributes:

- Student_ID
- Course_ID
- Semester
- Grade

---

**Key Concepts Used**

Primary Key
Each table contains a unique identifier to distinguish records.

Foreign Key
Relationships between tables are maintained using foreign keys.

Relational Model
The database follows a structured relational schema.

Data Integrity
Only valid and connected data is inserted into the database.

---

**SQL Operations Performed**

- Data insertion using INSERT statements
- Managing relationships between tables
- Checking stored data using SELECT queries

Example verification queries:

SELECT * FROM Department;
SELECT * FROM Faculty;
SELECT * FROM Course;
SELECT * FROM Student;
SELECT * FROM Enrollment;

---

**Skills Practiced**

- Database design basics
- SQL query writing
- Understanding table relationships
- Data organization in DBMS

---

**Conclusion**

This lab helped in understanding how a real database works and how multiple tables interact with each other in a structured system.

---



DBMS Laboratory Assignment
Computer Science Engineering
