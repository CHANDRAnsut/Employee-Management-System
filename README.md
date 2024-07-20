# Employee-Management-System

An Employee Management System is a software application used by organizations to manage their employee data. It helps to keep track of employee information such as their personal details, job position, salary, and other related data. It is designed to streamline HR operations and automate administrative tasks related to employees.


The above code starts from the while loop and that is the user view means first time the user interacts with the options provided there.

On choosing the options user is asked for the necessary details to be added.

A list employees = [] has been declared globally to add employees with their details in the form of dictionary. It is declared globally so that it is available throughout the program.

add_employee() function is defined to add the employee which takes the employee id from the user and checks whether any user with the ID provided exists or not. If yes then a message is displayed that user already exist otherwise the details are added in the form of dictionary in the list employees[] declared globally

update_employee() function updates the employee details by taking the user id and finds the employee with that employee id and displays a submenu to the user asking which detail user want to update. Each option shows its old value and asks for the new value from the user.

delete_employee() function deleted the employee on the basis of employee ID.

list_employees()function displays list of all the employees in the tabular format.

Inside these functions on few places return is used to return the control to the while loop if the employee is found and the necessary operation is performed successfully. If the employee is not found then this return statement will not be executed as the control will not come inside the if block then a message Employee not found is displayed to the user.
