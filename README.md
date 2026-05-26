# staffsync
# StaffSync — Employee Attendance & Payroll System

## About
Backend REST API for managing employee records, daily 
attendance tracking and monthly payroll processing.

## Tech Stack
Java · Spring Boot · MySQL · Spring Data JPA · Git

## Features
- RESTful APIs for Employee, Attendance and Payroll management
- Large-scale data handling with pagination and filtering
- OOP-based modular service-layer design
- Payroll auto-calculation based on attendance records
- Git version control with feature-branch workflow

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/employees | Get all employees (paginated) |
| POST | /api/employees | Add new employee |
| GET | /api/employees/{id} | Get employee by ID |
| POST | /api/attendance | Mark attendance |
| GET | /api/attendance/{empId} | Get attendance records |
| GET | /api/payroll/{empId} | Get payroll summary |

## Database Schema
- Employee (id, name, department, role, salary, joinDate)
- Attendance (id, employeeId, date, status, hoursWorked)
- Payroll (id, employeeId, month, daysPresent, totalPay)

## Status
In progress
