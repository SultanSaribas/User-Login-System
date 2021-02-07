# USER REGISTER/LOGIN SYSTEM
**It is a User Login System Web Application. It includes the classes as follows;**
•	error.php
•	login.php
•	server.php
•	signup.php
•	welcome.php
•	style.css
•	styles.css

A local server needed to install to run this application. I installed xampp local server and I took advantage of Visual Studio Code IDE to code in PHP. 
This application consists of 3 web pages which are Log in Page, Sign up Page, Welcome Page. If a user did not enter both email and password information it gives an error and says “Please enter your email/password”. If the user does not have an account it gives an error and says “The user could not be found.”. In this case, the user should click the sign up link below to register the system. In the registration page, user should enter all information not to get errors and should confirm the password. If the confirmation password does not match the password, it gives error as well. When all information the user enter is properly full and passwords match, then it direct to Login page. Finally, the user can log in the system with the information he/she used for signing up the system. After all, the user can access the Welcome Page. In addition, if the user wants, he/she can log out using the link(directs to Login page) in the Welcome page.
The local links for this web application as follows;
http://localhost/LoginSystem/login.php   //Log in Page
http://localhost/LoginSystem/signup.php  //Registration Page
http://localhost/LoginSystem/welcome.php  //Welcome Page

**SQL Queries;**
```
•	INSERT INTO users (name, surname, email, password)
VALUES ('$name', '$surname', '$email', '$createpassw')
•	SELECT * 
FROM users
WHERE email = '$email' AND password='$createpassw'
```
