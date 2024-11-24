# Employee-Management-System
The Employee Management Application is a console-based application developed in Java, designed to manage employee records effectively. This application allows the user to perform CRUD (Create, Read, Update, Delete) operations on employee data, making it a simple yet powerful tool for managing an organization's workforce.

## Core Features
  ### Add Employee:
    Allows users to create new employee records.
    Users input details such as ID, name, age, designation, department, and salary, which are stored in a HashSet.
  ### View Employee:
    Retrieves and displays details of a specific employee based on the unique employee ID.
    Validates the ID to ensure the record exists.
  ### Update Employee:
    Enables updating employee information, such as name and salary, based on their ID.
    Ensures data consistency and informs the user if the record doesn't exist.
  ### Delete Employee:
    Allows users to remove an employee's record by ID.
    Validates the existence of the record before deletion.
  ### View All Employees:
    Displays the details of all employees in the system.
    Useful for reviewing the current workforce.
  ### Exit:
    Gracefully terminates the application.

## Modules and Classes
  ### Main Class (Main.java):
    Acts as the entry point of the application.
    Displays a menu-driven interface for user interaction.
    Processes user inputs to invoke corresponding methods in the EmployeeService class.
  ### Service Class (EmployeeService.java):
    Contains the business logic for the application.
    Manages a collection of employee records using a HashSet, ensuring no duplicate records.
    Handles operations such as adding, updating, viewing, and deleting employees.
  ### Entity Class (Employee.java):
    Represents the data model for an employee.
    Encapsulates properties like ID, name, age, designation, department, and salary.
    Implements getters and setters for encapsulation and provides a toString method for meaningful output.

## Key Functionalities
  ### Data Storage:
    Uses a HashSet to store employee objects, ensuring unique employee entries.
  ### Input Validation:
    Checks user inputs, such as IDs, before performing operations to ensure data accuracy.
  ### Scalability:
    The modular design allows for easy integration of additional features, such as database connectivity.
  ### User-Friendly Interface:
    Presents a straightforward menu for navigation, making it easy to use for non-technical users.

## Example Workflow
  1. A user runs the application and is greeted with a menu.
  2. They choose to Add Employee and input details like:
    ID: 105
    Name: Alice
    Age: 30
    Designation: Project Manager
    Department: IT
    Salary: 85,000
  3. The application stores the record and confirms the addition.
  4. Later, the user views the details of this employee by entering their ID.
  5. If required, the user can update Alice's salary or remove her record entirely.

## Advantages of the Application
  ### Efficiency: Simplifies employee data management with minimal overhead.
  ### Flexibility: Easily extendable to include advanced features like database integration or a GUI.
  ### Reliability: Ensures data consistency and prevents duplicate entries through the use of a HashSet.

## Potential Enhancements
  ### Database Integration:
    Replace the in-memory HashSet with a database for persistent data storage.
  ### Graphical User Interface (GUI):
    Develop a GUI using frameworks like JavaFX or Swing for a more intuitive user experience.
  ### Authentication:
    Add user roles and authentication mechanisms to secure data access.
  ### Search Functionality:
    Introduce advanced filters to search employees based on criteria like department or salary range.

The Employee Management Application is a fundamental project that demonstrates effective use of Object-Oriented Programming (OOP) principles, data structures like HashSet, and Java's core functionalities to build a practical, real-world solution.
