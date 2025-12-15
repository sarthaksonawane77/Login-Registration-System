Login & Registration System (Java Web Project)

Project Description:
-This project is a simple Login and Registration System built to understand how a web application works end-to-end using HTML/CSS frontend, Java backend, and MySQL database.

-The main focus of this project is learning how different tools and technologies interact with each other in a real-world web application.

Technologies & Tools Used:
-Frontend: HTML, CSS
-Backend: Java (Servlets)
-Server: Apache Tomcat
-Database: MySQL
-Database Connectivity: JDBC
-Security: Password hashing using SHA-256
-IDE: VS Code

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


Application Flow:
  -User opens login or registration HTML page in browser
  -User enters credentials and submits the form
  -Data is sent to backend using POST request
  -Java Servlet receives and validates the input
  -Password is hashed using SHA-256
  -Data is stored or verified in MySQL database using JDBC
  -Result is sent back to browser as response

Key Features:
  -User registration with input validation
  -Secure password storage using hashing
  -Login authentication using database verification
  -Clear separation of frontend, backend, and database
  -Learning Outcome
  -Understood how HTML/CSS frontend communicates with Java backend
  -Learned role of Apache Tomcat and Servlets
  -Practiced JDBC connectivity with MySQL
  -Gained knowledge of basic web security (password hashing)
  -Learned importance of project structure and separation of concerns

Note:
-This project was built as a learning-focused web application to understand the interaction between different layers of a Java web system rather than advanced UI or frameworks.
