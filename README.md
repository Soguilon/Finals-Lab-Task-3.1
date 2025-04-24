# [Finals-Lab-Task-3.1](https://github.com/user-attachments/files/19892458/Finals.Task.3.Using.MYSQL.Clause.Soguilon.docx)
- This portfolio demonstrates basic SQL skills through the use of MySQL queries. It involves managing an online course database by performing data retrieval, aggregation, and sorting based on a pre-existing dataset.

## Step by Step Process
- **Step 1: Create the Database**
  - Open your MySQL environment (like MySQL Workbench or phpMyAdmin).
  - Create a new database by typing the command:
    - `CREATE DATABASE online_courseDB;`
  - This command sets up the main storage space for your online course data.

- **Step 2: Select the Database**
  - Choose or switch to the newly created database to start working in it:
    - `USE online_courseDB;`
  - This ensures all tables and queries will be applied to the correct database.

- **Step 3: Load Initial Data**
  - Download the `onlineCourse.l` file provided in the instructions.
  - Run or import this file into the MySQL environment.
    - It will automatically:
      - Create a table called `courses`.
      - Add 20 course records into the table.
  - Make sure the table has the following fields:
    - `id`: auto-incremented primary key.
    - `course_name`: VARCHAR, not null.
    - `category`: VARCHAR, not null.
    - `enrollment_limit`: INTEGER, not null.
    - `students_enrolled`: INTEGER, not null.

- **Step 4: Perform SQL Tasks in Order**

  - **Task 1: List Courses Below Capacity**
    - Find and display all courses where the number of enrolled students is less than the enrollment limit.
    - SQL Concept: `SELECT` with `WHERE` condition.

  - **Task 2: Group by Category**
    - Group the courses by their category and show the total number of enrolled students per category.
    - SQL Concepts: `GROUP BY` and `SUM()` function.

  - **Task 3: Show Fully Enrolled Courses**
    - Display courses where the number of students enrolled equals the enrollment limit.
    - SQL Concept: Equality condition in `WHERE`.

  - **Task 4: Total Students in All Courses**
    - Calculate and display the total number of students enrolled across all 20 courses.
    - SQL Concept: Aggregation using `SUM()`.

  - **Task 5: Sort Courses by Enrollment**
    - Display all courses ordered by the number of students enrolled, from lowest to highest.
    - SQL Concept: `ORDER BY` with ascending sort.

- **Final Step: Review Results**
  - Check that each query produces the expected output.
  - Verify correct field names and data consistency.



#Screenshots
## Query Statements

1.) Task 1
- ![Image](https://github.com/user-attachments/assets/deb92121-c6f0-4d44-9dc7-0e74c9d2ec93)

2.) Task 2
- ![Image](https://github.com/user-attachments/assets/169f8f3e-1e01-467f-8c1c-d5b2be644ee4)

3.) Task 3
- ![Image](https://github.com/user-attachments/assets/f3d8c1b5-a4b8-4548-b0c3-69e99bf9c1d0)

4.) Task 4
- ![Image](https://github.com/user-attachments/assets/ecca46a5-575f-4bb6-9185-92e39df316a8)

5.) Task 5
- ![Image](https://github.com/user-attachments/assets/2c881e0c-8a2d-4463-a492-8f0d3be7530d)

## Output of Query Statements

1.) Task 1
- ![Image](https://github.com/user-attachments/assets/15971fe6-c314-42d6-8fda-0a34f6a2fb00)

2.) Task 2
- ![Image](https://github.com/user-attachments/assets/f532ce24-0488-4c40-9d42-813272ebe438)

3.) Task 3
- ![Image](https://github.com/user-attachments/assets/e6afeff3-018a-4702-8b24-bd0f3e55725e)

4.) Task 4
- ![Image](https://github.com/user-attachments/assets/c93cc7ad-3f0b-4794-a981-2e0a7ce842e7)

5.) Task 5
- ![Image](https://github.com/user-attachments/assets/63173b6b-9ad1-4a0d-9eb8-ce9eabfbe02e)
