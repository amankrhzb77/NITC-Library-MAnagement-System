
# NITC Library Management System

This comprehensive Library Management System was developed for NITC to streamline book management and user interactions. The system provides a user-friendly interface for library staff and members to manage books, track borrowings, and handle returns efficiently.


## Features

- User Authentication and Authorization
- Book Management (Add, Update, Delete)
- Member Management (Register, Update, Delete)
- Book Borrowing and Returning
- Search Functionality for Books and Members
- Overdue Book Alerts


## Technology Stack
- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Database: MySQL

  
## Installation



    
### Prerequisites
 - PHP
 - MySQL
 - Apache(Web server)
 
### Steps

1.Clone the repository: 

  ```bash
  git clone https://github.com/amankrhzb77/NITC-Library-MAnagement-System.git
  cd NITC-Library-MAnagement-System
  ```
  2.Configure the database:

- Create a database named library_db.
- Import the SQL file located at database/library_db.sql to set up the database schema and initial data.

3.Update the database configuration in the config.php file with your MySQL credentials:

    <?php
    $servername = "localhost";
    $username = "your_username";
    $password = "your_password";
    $dbname = "library_db";
    ?>

4.Start the backend server:

  - If using a local server, place the project in the server directory (e.g., htdocs for XAMPP).
- Start the server.

5.Open a web browser and navigate to http://localhost/library-management-system to access the application.

## Usage

1.Register as a new user or log in with existing credentials.

2.Use the dashboard to manage books, members, borrowings, and returns.

3.Utilize the search functionality to find specific books or members.

4.Monitor and manage overdue books and alerts.
## Contributing


1.Fork the repository on GitHub.

2.Create a new branch from the main branch.

3.Make your changes and commit them with descriptive messages.
    
4.Push your changes to your forked repository.
    
5.Open a pull request on the original repository and provide a detailed description of your changes

