# Student Management System

Built with modern technologies, this system offers a comprehensive set of features for efficiently managing student data and facilitating administrative tasks.

<div align="center">
  <img width="1024" alt="Screenshot 2024-03-27 at 11 57 55 PM" src="https://github.com/YaChunT/student_management_system/assets/162515094/fb15cbc0-3fd9-44df-b77c-9fad4bc9a874">
</div>

## Table of Contents
- [About](#about)
- [Architecture Diagram](#architecture-diagram)
- [Coverage Examples](#coverage-examples)
- [Show me the code](#show-me-the-code)

## About📌  
This Student Management System is designed to streamline the process of managing student data and administrative tasks. Here are the key details:

- **Features**: 
  - Interactive dashboard
  - Information management
  - Result generation
  - Leave application

- **APIs**: 
  - Provides APIs for creating, getting, updating, and deleting student data.

- **Dependencies**: 
  - Maven 4.0.0
  - Spring Boot 3.2.3
  - Java 21

- **Technologies**: 
  - HTML5
  - CSS3
  - JavaScript (JS)
  - PostgreSQL

## Architecture Diagram 🏗️

<div align="center">
  <img width="1024" alt="Screenshot 2024-03-27 at 11 55 14 PM" src="https://github.com/YaChunT/student_management_system/assets/162515094/d8a7dd63-da8c-4d71-9693-0112be5e0511">
</div>

<div>
This web application architecture is designed around user management and security, encompassing several key components:
</div>

- **User Registration**: New users can create accounts within the system through this process.
- **Roles**: Upon registration, users are assigned roles such as 'admin' or 'user', dictating their access levels within the application.
- **Spring Security**: Leveraging a robust authentication and access-control framework for Java applications, Spring Security effectively manages the security aspects of the application.
- **Session Timeout**: Sessions expire after 15 minutes, requiring users to re-authenticate for continued access.
- **Java Mail Sender**: Integrated to facilitate email communications from the application, including functionalities such as email verification during registration.

This architecture follows a standard pattern for user management and security in web applications, ensuring that only authenticated and authorized users can access designated features or sections.


## User Interface 📊 
- **Sign-in page for web application**
<div align="center">
<img width="1506" alt="Screenshot 2024-03-28 at 12 17 49 AM" src="https://github.com/YaChunT/student_management_system/assets/162515094/8edefba6-8586-4f4a-9039-5e42b29a35ee">
</div>

## Getting started 🏃‍♂️ 

1. Clone this repository:

    ```bash
    git clone https://github.com/YaChunT/student_management_system.git
    ```

2. Navigate into the project directory:

    ```bash
    cd student_management_system
    ```

3. Build the project using Maven:

    ```bash
    ./mvnw clean package
    ```

4. Run the application:

    ```bash
    java -jar target/student_management_system-0.0.1-SNAPSHOT.jar
    ```

5. The application will start running at `http://localhost:8080`.
