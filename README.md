# Employee-Management-System
A list employees = [] has been declared globally to add employees with their details in the form of dictionary. It is declared globally so that it is available throughout the program.

add_employee() function is defined to add the employee which takes the employee id from the user and checks whether any user with the ID provided exists or not. If yes then a message is displayed that user already exist otherwise the details are added in the form of dictionary in the list employees[] declared globally

update_employee() function updates the employee details by taking the user id and finds the employee with that employee id and displays a submenu to the user asking which detail user want to update. Each option shows its old value and asks for the new value from the user.

delete_employee() function deleted the employee on the basis of employee ID.

list_employees()function displays list of all the employees in the tabular format.

Inside these functions on few places return is used to return the control to the while loop if the employee is found and the necessary operation is performed successfully. If the employee is not found then this return statement will not be executed as the control will not come inside the if block then a message Employee not found is displayed to the user.
empolyess can built analysis data
