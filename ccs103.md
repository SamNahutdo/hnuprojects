# MCDO PAYROLL SYSTEM USING C

***CCS 103 FINAL PROJECT***

Members

Sam Nahutdo - Programmer

Marchus ********

David *******


*******
These are teacher based suggestions in our system, so this is well presented.
*******
***🔧 Functions and Their Uses***

*Function Name	Purpose*

main()____________Entry point. Loads data from file and shows the main menu.

mainMenu()_________Displays the main options: Admin, Employee, or Exit.

verifyPin()________Asks for a PIN and verifies it for admin access.

adminMenu()________Displays the admin features like viewing, adding, and updating employees.

viewEmployees()____Lists all employees with their details and calculated salary.

addEmployee()______Adds a new employee to the system.

updateEmployee()___Modifies employee's name or position.

removeEmployee()___Deletes an employee by shifting arrays to remove their data.

deductSalary()_____Applies salary deductions (SSS, PhilHealth, Pag-Ibig).

employeeMenu()_____Menu for employee-specific actions (not shown in full yet).

viewBalance(int)___Views salary balance for a specific employee.

viewDeducted(int)__Views the amount and reason for salary deductions.

findEmployee(int)__Searches employee by ID and returns index, or -1 if not found.

saveToFile()_______Saves all employee data to a file for persistence.

loadFromFile()_____Loads employee data from the file when the system starts.

viewAttendance()___Displays attendance logs (if implemented).

markAttendance()___Marks clock-in and clock-out for employees (if implemented).



*******

***📚 Arrays Used and Their Purposes***

*Array Name_____________Type_____________Description*

ids[]__________________int______________Stores unique ID for each employee.

names[][]______________char(2D array)___Stores names of employees (max 50 characters).

positions[][]__________char(2D array)___Stores job titles (Service Crew, Cooker, etc.).

salaries[]_____________int______________Daily salary for each employee depending on position.

deductions[]___________int______________Total amount deducted from each employee's salary.

deductionReason[][]____char(2D array)___Stores explanation or reason for deductions.

hoursWorked[]__________float____________Hours worked (not fully shown/used in the code yet).

lastPaidDay[]__________int______________Tracks the last day the salary was paid (for 7-day period).

clockIns[]_____________int______________Count of clock-in events.

clockOuts[]____________int______________Count of clock-out events.

daysWorked[]___________int______________Number of full workdays completed.

isClockedIn[]__________int______________(0/1)	Boolean to check if employee is currently clocked in.

lastIn[]_______________time_t___________Stores last clock-in time (used for attendance tracking).

lastOut[]______________time_t___________Stores last clock-out time.

balances[]_____________int______________Tracks salary available to be withdrawn.


*******

***🔤 Strings Used and Why***

*String/Char Array	Description*

names[i]________________Stores each employee's name (used for printing and searching).

positions[i]____________Stores job title; used for display and assigning salary.

deductionReason[i]______Holds a short explanation of the deduction reason.

FILENAME (macro)________Name of the file used for saving/loading employee data.

ID:_____________________Auto-assigned integers (1–20)


*******
- i will be updated the flowchart of how they work, the rest of the functions, strings, arrays, and how to use it

