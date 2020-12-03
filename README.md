Alexandra Koren  
IT FDN 130 A  
Assignment 07  

## UDFs  
UDFs, or User Defined Functions, are functions that are created by the user, as opposed to the built-in functions SQL already contains. They are used when a user wants to create and save a more complex query. There are two types of UDFs - scalar, which return one value, and table-valued, which return tables. Since functions can take parameters, UDFs are also useful when you want to run the same stored query with different values. 

## Types of UDFs    
A scalar function, as mentioned above, is a function that returns only a single value, such as a number or a string. Some examples of this type of function are those that already exist in SQL - AVG(), MAX(), MIN(), etc.
An inline function, on the other hand, returns a table, but only SELECT statements are allowed in the function. 
A multi-statement function is similar to an inline function in that it returns a table, but it allows more involved statements than just SELECT. 
