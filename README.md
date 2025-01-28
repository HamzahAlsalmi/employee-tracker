Employee Tracker
Description
The Employee Tracker is a command-line application built with Node.js, Inquirer, and PostgreSQL to help manage employee data. You can:

View all departments, roles, and employees
Add new departments, roles, and employees
Update employee roles
Technologies Used
Node.js
Inquirer
PostgreSQL
pg (PostgreSQL client for Node.js)
Installation
Clone this repository:

bash
Copy
git clone git@github.com:HamzahAlsalmi/employee-tracker.git
Install dependencies:

bash
Copy
cd employee-tracker
npm install
Set up PostgreSQL:

Create a database.
Run schema.sql to set up the tables.
Start the app:

bash
Copy
npm start
Features
View All Departments, Roles, and Employees
Add Department, Role, and Employee
Update Employee Role
Walkthrough Video
Check out the video demo here:
https://drive.google.com/file/d/1_1xNa9tFbkMs_D3lqT9IChLxkw12x7Xs/view

Database Schema
department: Stores department info (id, name).
role: Stores role info (id, title, salary, department_id).
employee: Stores employee info (id, first_name, last_name, role_id, manager_id).
Usage
Run the app with npm start.
Select an option from the menu (view, add, or update data).
Follow the prompts to enter information.
Repository Structure
lua
Copy
/employee-tracker
  |-- /node_modules
  |-- schema.sql
  |-- index.js
  |-- package.json
  |-- README.md
License
This project is open-source under the MIT License.
