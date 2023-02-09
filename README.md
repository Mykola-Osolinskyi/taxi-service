# 🚕 Taxi-Service 🚕
### Project description:
```
A simple web-application that supports authentication, registration and other CRUD operations.
```
## 🎯 Features:
- registration like a driver;
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update a driver;
- display list of all manufacturers;
- display list of all cars;
- display list of all drivers;
- add driver to car.
### 📂 Project structure (3-layer architecture):
- DAO - Data access layer - here 
  you can see all logic to work with DB
- Service - Application logic layer
- Controllers - Presentation layer
## :gear: Used technologies and libraries:
- Java (JDK 11)
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP and JSTL
- HTML/CSS
- Checkstyle plugin
## ㊗️ Steps to run the app on your computer:
- Clone the repo [from here](https://github.com/Mykola-Osolinskyi/taxi-service);
- Install MySQL;
- Configure Apache Tomcat version: 9.0.71;
- Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- Now the application is ready to use!
- I hope this app will be helpful for you!
