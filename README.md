# Employee-Management-System
Employee Management System using (SPRING BOOT) And  (JAVA ) &amp; (POSTMAN)  * MYSQL
#ASSUMPTIONS#

DATABASE and TABLES are created in MySQL
EMployeeID is a foreign key in Employee table.
Make sure department table is populated with the department you refer for in employee.
While inserting employee detail through postman service: give a department id for department.

               **   Employee ID - AUTO GENERATED 
 Eg: {
        "firstName": "SHYAM",
        "lastName": "GUPTA",
        "department": "CSE",
        "designation": "Teacher",
        "phone": "33332",
        "salary": 20000.0
}
#TECHNOLOGY STACK#

Java
IntelliJ IDEA
MySQL Workbench
Postman for Chrome: Version 4.10.5 

#DESIGN DISCUSSION#

The employee table has a department id foreign key.
Department table needs to have a value existing to be referred by the employee table.
Get mapping will fetch the results, Post mapping will insert results, Put mapping and Patch mapping will update results, Delete mapping will delete results.
You will need to create database if not, change in the application.properties file.
Ease of extending the program
You can add EMPLOYEE table and assign username and password details for the employee.
You can also create a system account who handles all the creation and deleting of employee.
