# Week-12_Employee-Tracker
A command-line application for managing a company's employees using node, inquirer, and MySQL.


### User story
```md
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business
```
## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Questions](#questions)  

## Installation
- This application need node.js, please refer to [offical website](https://nodejs.org/en/download/) for installation
- download this repo by running
    ```bash
    git clone : https://github.com/ausamindec/Week-12_Employee-Tracker.git
    ```
- This application also need to install mysql on your computer, please refer to [mysql website](https://www.mysql.com/downloads/) for installation
- Change password in ```index.js``` to your root user password of your mysql DBMS.
- install required node pacakges by running
    ```bash
    npm install
    ```
- Create schema of database tables by running all the queries in ```schema.sql```
- Set up test records yourself or run queries in ```seed.sql```
- start the application by running
    ```
    node index
    ```
    or
    ```
    npm start
    ```


## Usage
A command-line application that at a minimum allows the user to:
- Add departments, roles, employees (one row at a time)
- View departments, roles, employees
- Update employee roles
- Update employee managers
- View employees by manager
- Delete departments, roles, and employees (one row at a time)

### 
<h1 align="center">
    <a href="https://drive.google.com/file/d/1jkLcPTya4VeHd8YzFLy4ORIoPeSX3_-k/view?usp=sharing" target="_blank">
     View Walkthrough Video
    </a>
</h1>

### walkthrough GIF
![employee-tracker]()

### Constraints
```md
To delete/update a department will also delete/update roles within the department

To delete a role will be rejected if any employee was given this role, and an error will be thrown; to update a role will also update every employee with the role

To delete a manager will set all report-tos manager to NULL, i.e. with no manager 
```

## License
N/A
  
## Tests
Terminal run this application  
## Questions
connect with me on [my Github](https://github.com/ausamindec) and if you have additional questions, please email me at: ausamindec@gmail.com


