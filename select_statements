- SELECT STATEMENET

#Now remember we can just select everything by saying:
SELECT * 
FROM parks_and_recreation.employee_demographics;


#Let's try selecting a specific column
SELECT first_name
FROM employee_demographics;

SELECT first_name, last_name
FROM employee_demographics;



SELECT last_name, first_name, gender, age
FROM employee_demographics;

#You'll also often see SQL queries formatted like this.
SELECT last_name, 
first_name, 
gender, 
age
FROM employee_demographics;

#The query still runs the exact same, but it is easier to read and pick out the columns
#being selected and what you're doing with them.



#You can see here we have the total_money_spent - we can perform calculations on this
SELECT first_name,
 last_name,
 total_money_spent,
 total_money_spent + 100
FROM customers;



#Math in SQL does follow PEMDAS which stands for Parenthesis, Exponent, Multiplication,
#Division, Addition, subtraction - it's the order of operation for math

#For example - What will the output be?:
SELECT first_name, 
last_name,
salary,
salary + 100
FROM employee_salary;
#This is going to do 10* 100 which is 1000 and then adds the original 540

#Now what will the output be when we do this?
SELECT first_name, 
last_name,
salary,
(salary + 100) * 10
FROM employee_salary;


# Pemdas

#One thing I wanted to show you about the select statement in this lesson is the DISTINCT Statement - this will return only unique values in
#The output - and you won't have any duplicates

SELECT department_id
FROM employee_salary;

SELECT DISTINCT department_id
FROM employee_salary;

