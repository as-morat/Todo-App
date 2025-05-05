# Simple Todo App

A basic todo application built with Spring Boot and Thymeleaf.
---
![image](https://github.com/user-attachments/assets/ecebb2b9-3832-4c1d-885a-e8795903c5f0)
---
## Features
- Add new tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Responsive Bootstrap UI

## Technologies
- Java 17
- Spring Boot 3
- Thymeleaf
- Bootstrap 5
- MySQL

## Setup

1. **Database Configuration**:
   - Create a MySQL database named `todo`
   - Update `application.properties` with your credentials:
     ```properties
     spring.datasource.username=your_username
     spring.datasource.password=your_password
     ```

2. **Run the Application**:
   ```bash
   mvn spring-boot:run
