Login & Registration System (Java Web Project)

Project Description:
This project is a simple Login and Registration System built to understand how a web application works end-to-end using HTML/CSS frontend, Java backend, and MySQL database.

The main focus of this project is learning how different tools and technologies interact with each other in a real-world web application.

## Technologies & Tools Used

1. Frontend: HTML, CSS
2. Backend: Java (Servlets)
3. Server: Apache Tomcat
4. Database: MySQL
5. Database Connectivity: JDBC
6. Security: Password hashing using SHA-256
7. IDE: VS Code

## Project Structure

```text
login-registration-project/
├── frontend/
│   ├── login.html
│   ├── register.html
│   └── style.css
├── backend/
│   ├── LoginServlet.java
│   ├── RegisterServlet.java
│   ├── DBConnection.java
│   └── PasswordHashUtil.java
└── database/
    └── schema.sql
```


## Application Flow

1. User opens login or registration HTML page in browser
2. User enters credentials and submits the form
3. Data is sent to backend using POST request
4. Java Servlet receives and validates the input
5. Password is hashed using SHA-256
6. Data is stored or verified in MySQL database using JDBC
7. Result is sent back to browser as response

## Key Features

1. User registration with input validation  
2. Secure password storage using hashing  
3. Login authentication using database verification  
4. Clear separation of frontend, backend, and database  

## Learning Outcome

1. Understood how HTML/CSS frontend communicates with Java backend  
2. Learned role of Apache Tomcat and Servlets  
3. Practiced JDBC connectivity with MySQL  
4. Gained knowledge of basic web security (password hashing)  
5. Learned importance of project structure and separation of concerns  


Note:
This project was built as a learning-focused web application to understand the interaction between different layers of a Java web system rather than advanced UI or frameworks.
