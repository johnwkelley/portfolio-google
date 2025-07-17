# Apply filters to SQL queries

## Project description

Viewing the log\_in\_attempts tables

## Retrieve after hours failed login attempts

SELECT \* from log\_in\_attempts WHERE login\_time \> “17:00” AND success \= FALSE;

## Retrieve login attempts on specific dates

SELECT \* from log\_in\_attempts WHERE login\_date \= ‘2025-05-15”;

## Retrieve login attempts outside of Mexico

SELECT \* FROM log\_in\_attempts WHERE location \!= “MEX”

## Retrieve employees in Marketing

SELECT \* FROM employees WHERE department \= “Marketing”;

## Retrieve employees in Finance or Sales

SELECT \* FROM employees WHERE department \= “finance” OR department \= “sales”

## Retrieve all employees not in IT

SELECT \* FROM employees WHERE department \!= “IT”;

## Summary

Select queries can be versatile to match the need of the query, as well as used to target specific types of data and tables.   
