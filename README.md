# Employee-Management-and-security-system
![pro](https://github.com/Tanmay2484/Employee-Management-and-security-system/assets/103728522/16278c6d-6893-4e03-b55e-8487e9c605e2)
![pro](https://github.com/Tanmay2484/Employee-Management-and-security-system/assets/103728522/af85d410-28ac-4a32-bbac-4594592ab4dd)


https://github.com/Tanmay2484/Employee-Management-and-security-system/assets/103728522/33fc3f28-317f-49ef-8207-3e81b32a9ac4



This project is an Employee Management System that demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations using object-oriented programming (OOP) concepts, along with security features such as login, logout, and signup operations.

CRUD Operations:

Create: Users can input employee details, creating new employee records in the system.
Read: Users can list all employees, search for employees by ID, name, or position, and view employee details.
Update: Users can modify employee information, including name, gender, position, and salary.
Delete: Users can remove employee records from the system.
Object-Oriented Programming (OOP):

The project employs OOP principles with the Employee class, which encapsulates employee attributes (id, name, gender, position, salary) and behavior (input, output, validation).
The class uses getter and setter methods to encapsulate data and ensure data integrity.
Static methods of the class allow for operations that apply to all employees, such as sorting and searching.
Security Features:

Login: Users must provide their employee ID and password to access the system. Passwords are validated to meet specific criteria (length, capital letter, special characters).
Logout: Users can log out of the system to protect their session from unauthorized access.
Signup: Users can create a new employee profile, including a password during signup. Password creation follows strict rules to enhance security.
In summary, this project demonstrates how to implement CRUD operations within an object-oriented framework, emphasizing security through user authentication (login and signup) and session management (logout). It provides a practical example of using C++ to build a simple but functional employee management system with these features.

How this project works

Employee Class:

The project starts with the definition of the Employee class, which represents individual employees.
The class contains private member variables such as id, name, gender, position, salary, and password.
Member Functions:

The Employee class has member functions to set and get the employee's attributes, such as setName, setGender, setSalary, etc.
There is also a function input to input employee details interactively, including password validation.
The isValidPassword function checks if the entered password meets certain criteria.
The output function displays an employee's details in a formatted manner.
Main Function:

The main function sets up the main menu for the program and manages user interactions.
Vector of Employees:

A vector employees is used to store instances of the Employee class, effectively creating a database of employees.
User Authentication:

Users can either sign up or log in.
During signup, users create an employee profile with their details, including a password.
Passwords must meet specific criteria (e.g., length, starting with a capital letter, containing special characters).
Main Menu:

After authentication, users can choose from several options in the main menu, depending on whether they are logged in or not.
Logged-In State:

If the user logs in successfully, they enter a logged-in state and gain access to additional options.
Employee Management:

Users can input new employee details, list all employees, search for employees by ID, name, or position, sort employees by name or salary, delete employees, or update employee information.
Logout and Exit:

Users can choose to log out, which returns them to the main menu or exit the program entirely.
Flow Control:

The program uses loops and switch statements to navigate between menu options and sub-menus.
It ensures proper user authentication and authorization for certain actions (e.g., editing employee information).
Data Persistence:

Employee data is stored in memory as long as the program is running. However, it is not saved to a file for persistence beyond the current session.
Input Validation:

Throughout the program, there is input validation to ensure that users provide valid data and follow specific rules (e.g., password validation).
User-Friendly Output:

Employee data is displayed in a well-formatted table-like format, making it user-friendly.
Security Considerations:

The program validates passwords and ensures that only authorized users can make changes to employee data.
Exit and Error Handling:

Users can choose to exit the program gracefully, and the program handles invalid input gracefully with error messages.




