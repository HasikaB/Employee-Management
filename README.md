# Employee-Management
Technology : Java ,MySQL

Introduction:
The Employee Management System is a Java Swing application designed for efficiently managing employee records. It utilizes a graphical user interface (GUI) for easy interaction with a MySQL database, enabling CRUD operations.

Features:
The application provides key features such as adding new employees, updating existing records, deleting entries, and searching for specific employees.

Prerequisites:
To run the Employee Management System, ensure you have Java Development Kit (JDK) installed, a running MySQL Server, and the MySQL Connector/J library available.

Setup:

Clone or download the source code.
Open the project in a Java Integrated Development Environment (IDE).
Ensure the required libraries, including MySQL Connector/J, are in the classpath.
Update MySQL connection details in the connect() method within the Employee class.
Database Connection:
Modify the MySQL connection details in the connect() method of the Employee class, including the URL, username, and password.

Running the Application:
Run the Employee class's main method.
The application window will appear, providing access to the main interface.

Code Structure:
The code is organized in a single class, Employee, responsible for handling GUI components, database connections, and executing SQL queries.

Database Schema:
Assumes a MySQL database named "Hashcompany" with a table named "employee," having columns for ID, employee name, salary, and mobile number.

Dependencies:
Depends on the MySQL Connector/J library for database connectivity. Ensure the library is added to the project's classpath.
