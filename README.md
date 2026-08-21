# Assignment 1 - Core SQL DDL and DML

## College Database

This assignment contains 10 SQL questions based on a college student database. It demonstrates the use of basic SQL commands for creating, inserting, retrieving, updating, and deleting student records.

**Database Name:** `CollegeDBS`

## Database Table

The assignment uses a table named `CollegeStudents`.

| Column      | Description                   |
| ----------- | ----------------------------- |
| StudentID   | Unique ID of the student      |
| StudentName | Name of the student           |
| Department  | Department of the student     |
| Age         | Age of the student            |
| Marks       | Marks obtained by the student |

## Sample Data

| StudentID | StudentName | Department             | Age | Marks |
| --------: | ----------- | ---------------------- | --: | ----: |
|       101 | Rahul       | Computer Science       |  19 |    85 |
|       102 | Priya       | Electronics            |  20 |    78 |
|       103 | Aman        | Mechanical             |  21 |    35 |
|       104 | Sneha       | Information Technology |  19 |    92 |

## Questions Covered

### Question 1 - CREATE

Create the `CollegeStudents` table with the required columns.

### Question 2 - INSERT

Insert the student record for Rahul into the table.

### Question 3 - INSERT

Insert three additional student records into the table.

### Question 4 - WHERE

Display all students who belong to the Computer Science department.

### Question 5 - UPDATE

Update the marks of the student with `StudentID = 101` from 85 to 90.

### Question 6 - UPDATE

Change Rahul's department to Information Technology.

### Question 7 - DELETE

Delete the student whose `StudentID = 103`.

### Question 8 - DELETE

Delete all students whose marks are less than 40.

### Question 9 - WHERE

Display the names of students whose marks are greater than 75.

### Question 10 - AGGREGATE FUNCTION

Find the highest marks obtained by a student using the `MAX()` aggregate function.

## SQL Concepts Used

* DDL (Data Definition Language)
* DML (Data Manipulation Language)
* `CREATE TABLE`
* `INSERT INTO`
* `SELECT`
* `WHERE`
* `UPDATE`
* `DELETE`
* `MAX()`

## Repository Structure

```text
Question1
Question2
Question3
Question4
Question5
Question6
Question7
Question8
Question9
Question10
README.md
```

## How to Run

1. Open MySQL.
2. Use the `CollegeDBS` database.
3. Open each question file.
4. Execute the SQL query.
5. Check the output.

## Author

**Sanika Kangane**
