# Employee Spring Boot CRUD

A simple Employee Management System developed using **Spring Boot** that provides REST APIs to perform CRUD (Create, Read, Update, Delete) operations on employee records.

## Features

- Add Employee
- View All Employees
- View Employee by ID
- Update Employee
- Delete Employee
- RESTful APIs
- Layered Architecture (Controller, Service, Entity)

## Technologies Used

- Java 17
- Spring Boot
- Maven
- Spring Web
- Eclipse IDE
- Postman

## Project Structure

```
src
 ├── main
 │    ├── java
 │    │    └── com.example.demo
 │    │          ├── controller
 │    │          ├── entity
 │    │          ├── service
 │    │          └── EmployeeSpringApplication.java
 │    └── resources
 │           └── application.properties
```

## REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/employees` | Get all employees |
| GET | `/api/employees/{id}` | Get employee by ID |
| POST | `/api/employees` | Add a new employee |
| PUT | `/api/employees/{id}` | Update employee |
| DELETE | `/api/employees/{id}` | Delete employee |

## Sample JSON

```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "department": "IT",
  "salary": 50000,
  "joinDate": "2026-07-14"
}
```
