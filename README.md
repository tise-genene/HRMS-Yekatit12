# HRMS - Yekatit 12 Hospital

*HRMS (Human Resource Management System)** is a web-based application developed for Yekatit 12 Hospital in Ethiopia to manage human resource operations efficiently. 
This project is built using HTML, CSS, JavaScript, PHP-CodeIgniter, and MySQL.

## Features

- **Employee Management**: Add, update, delete, and search employee records.
- **Attendance Management**: Track employee attendance and generate reports.
- **Leave Management**: Manage employee leave requests and approvals.
- **Payroll Management**: Calculate and manage employee payroll and deductions.
- **User Roles and Permissions**: Define different user roles and permissions for access control.
- **Responsive Design**: Mobile-friendly and responsive user interface.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP (CodeIgniter Framework)
- **Database**: MySQL
- **Other Tools**: jQuery, Bootstrap

## Getting Started

To get a copy of the project up and running on your local machine for development and testing purposes, follow these instructions:

### Prerequisites

- **Web Server**: [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/) or any server with PHP support.
- **PHP**: Version 7.4 or higher
- **MySQL**: Version 5.7 or higher
- **Composer**: Dependency Manager for PHP

### Installation

1. **Clone the repository**:
   git clone https://github.com/yourusername/HRMS-Yekatit12.git
   cd HRMS-Yekatit12

2. **Install dependencies**:
   composer install

3. **Set up the Database**:

  Create a MySQL database named hrms_yekatit12.
  Import the database schema located in the /database folder: hrms_yekatit12.sql.
  
4. **Configure Environment Settings**:

  Copy .env.example to .env and update the database credentials and other settings:
   cp .env.example .env
   
**Update the following lines in the .env file**:
    DB_DATABASE=hrms_yekatit12
    DB_USERNAME=your_username
    DB_PASSWORD=your_password
	 
5. **Run the Application**:
   Start your web server and navigate to http://localhost/HRMS-Yekatit12 in your web browser.

