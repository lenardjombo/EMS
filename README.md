# Employment Management System

## Screenshots

<img src="https://github.com/user-attachments/assets/f59499a4-f774-4767-9a3b-07833711ca91" alt="Screenshot from 2024-11-04 18-12-49" width="300" height="200" />
<br>
<img src="https://github.com/user-attachments/assets/c1919ac6-b7b5-44b7-a21e-0348543a4c08" alt="Screenshot from 2024-11-04 18-20-19" width="300" height="200" />
<br>
<img src="https://github.com/user-attachments/assets/ad20c427-0e6f-43d1-8c86-48ef1f7606ac" alt="Screenshot from 2024-11-04 18-20-38" width="300" height="200" />

## Overview

The Employment Management System is a simple web-based application built using Spring Framework that allows organizations to manage their employee records efficiently. This system provides a user-friendly interface for performing CRUD (Create, Read, Update, Delete) operations on employee data. It aims to streamline the process of managing employee information.

## Features

- **Employee Management**: Add, view, update, and delete employee records.
- **Responsive Design**: Accessible on various devices (desktops, tablets, and smartphones).

## Technologies Used

- **Backend**: Spring Boot, Spring MVC, Spring Data JPA
- **Database**: H2 Database (in-memory) or MySQL
- **Frontend**: Html and CSS
- **Build Tool**: Maven
- **Version Control**: Git
- **IDE**: IntelliJ IDEA 

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java 17 or higher
- Maven installed on your machine
- An IDE (e.g., IntelliJ IDEA, Eclipse)

## Getting Started

To get a local copy of the project up and running, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/employment-management-system.git`

2.**Build the Project**
  ```bash
  mvn clean install
```
3.**Run the Application**
   ```bash
    mvn spring-boot:run
```
4.Access the application: Open your web browser and go to `**http://localhost:8080**`

## API Endpoints

| Method | Endpoint               | Description                            |
|--------|------------------------|----------------------------------------|
| GET    | /api/employees         | Retrieve all employees                 |
| POST   | /api/employees         | Create a new employee                  |
| GET    | /api/employees/{id}    | Retrieve a specific employee by ID     |
| PUT    | /api/employees/{id}    | Update an existing employee            |
| DELETE | /api/employees/{id}    | Delete an employee by ID               |


**Contributing**
Contributions are welcome! Please follow these steps to contribute:

1.Fork the repository.
2.Create a new branch (`git checkout -b feature/YourFeature`).
3.Make your changes.
4.Commit your changes (`git commit -m 'Add some feature'`).
5.Push to the branch (`git push origin feature/YourFeature`).
6.Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to the Spring community for their extensive documentation and support.
