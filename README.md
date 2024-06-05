# SpringBoot + Hibernate
 
## 1. Project Setup
Set up your Spring Boot project using Spring Initializr (https://start.spring.io/) with the following dependencies:

- Spring Web
- Spring Data JPA
- Mysql Connector
- SpringBoot Dev Tools
- Database

- In pom.xml file of created springboot project use the version 2.7.15 of spring-boot-starter-parent and mysql-connector-j version as 8.0.33

## 2. Controller Layer
- Define a controller to handle HTTP requests.
## 3. Service Layer
- Create a service class to handle business logic.
## 4. Dao Layer
- Create a DAO class to interact with the database.
## 5. Entity Layer
- Create an entity class to map to the your created project table in your database.
## 6. Application.properties Layer
- Configure the database connection in src/main/resources/application.properties.
## 7. Testing API
- You can test the API using a tool like Postman or your web browser "https://localhost:8000/".
  
This setup provides a complete solution for creating an API in Spring Boot
