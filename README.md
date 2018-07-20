# MySQL Basic Queries

## The Assignment

You are the only DBA in the [JP Morgan](#) company right know, and your manager have asked you to bring the correct data from a confidential paper for a client. This is your opportunity to show your skills. Please, pay attention to the business questions.

## Deliverables

+ a github repository named `assignment--mysql-basic-queries` with a `.sql` file containing all answers.

###### Example

```sql
#1 Write a query to display all names from Products.

SELECT Id, Name FROM Products;
```

## Setup Instructions

  1. Connect to MySQL Server on [45.55.135.14/phpmyadmin](45.55.135.14/phpmyadmin)
  2. Copy the `HR` database and add your initial letters as suffix.

  ###### Example

  ```sql
  CREATE DATABASE HR_BG; # Bill Gates
  ```

## Exercise

```sql
# [Example]
# 0 Write a query to display the full name (FIRST_NAME + LAST_NAME) for all employees whose first name is 'John'.

SELECT FIRST_NAME, LAST_NAME
FROM Employees
WHERE
  FIRST_NAME = 'John';

# [Your Work Below]

# 1 Write a query to select all record from employees where last name in 'BLAKE', 'SCOTT', 'KING' and 'FORD'.


# 2 Write a query to display the full name (FIRST_NAME + LAST_NAME) and SALARY for all employees whose salary that is greater than $15,000.

# 3 Write a query to display the unique values of JOBS_ID available in the employees table.


# 4 Write a query to display the full name (FIRST_NAME + LAST_NAME) and DEPARTMENT_ID of all employees in departments 30 or 100 in ascending order.


# 5 Write a query to display the full name (FIRST_NAME + LAST_NAME) and SALARY for all employees whose salary is not in the range $10,000 through $15,000 and are in department 30 or 100.


# 6 Write a query to display the full name (FIRST_NAME + LAST_NAME) and HIRE_DATE for all employees who were hired in after July, 1 1987.


# 7 Write a query to display the first name of all employees who have both "b" and "c" in their first name.

# 8 Write a query to display the last name of employees whose names have exactly 6 characters.


# 9 Write a query to display the last name of employees having 'e' as the third character.


# 10  Write a query to display the last name, job, and salary for all employees whose job is that of a Programmer (IT_PROG) or a Shipping Clerk (SH_CLERK), and whose salary is not equal to $4,500, $10,000 or $15,000.

```
