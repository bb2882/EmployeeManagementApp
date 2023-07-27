# Employee Management App

![Section 1](https://github.com/bb2882/ReactEmployees/assets/70382872/79ff1cb6-2537-4557-af0a-3f2742e1d791)

## Overview

This is an Employee Management App built with React. It allows you to manage a list of employees, search for employees by name, and filter them based on certain criteria. Additionally, you can award employees and mark them for promotion.

### Total Number of Employees and Awards

Currently, there are 3 in the system, and 0 employees are eligible for awards. Please note that the number of awarded employees can be adjusted as you add more employees in the future.

## Features

### Search Bar and Filter

The app provides a search bar that allows you to search for employees by their names. Below the search bar, there is a filter box containing the following buttons:

- **All Employees:** Show all employees in the list.
- **On Promotion:** Show employees marked for promotion.
- **Salary > $1000:** Show employees with a salary greater than $1000.

Clicking on any of these filter buttons will display the employees who meet the corresponding criteria.

### Employee List

In this section, you can view the list of employees along with their names and salaries. Each employee entry has two buttons: **Delete** and **Award**.

- **Delete:** Clicking this button will remove the employee from the list.
- **Award:** Clicking this button will mark the employee as eligible for an award.
- **Promote** Clicking on employee will indicate that he should be promoted. A star icon will appear next to the button to indicate the employee's eligibility.

### Add Employee

To add a new employee, go to the "Add Employee" section. Here, you can provide the employee's name and salary in the input fields and click the **Add** button. The new employee will be added to the employee list.

## Getting Started

To run this project on your local machine, follow these steps:

1. Clone the repository:

```
git clone https://github.com/bb2882/ReactEmployees.git
```

2. Install dependencies:

```
npm install
```

4. Start the app:

```
npm start
```

The app will open in your default web browser, and you can begin managing your employees.

## Contributing

If you find any issues or have suggestions to improve this project, feel free to create an issue or submit a pull request on the GitHub repository.

## Note

This project is designed to provide a simple and understandable UI for managing employees. Feel free to extend its functionalities and customize it according to your specific needs.
