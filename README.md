# ToDo List API
_This is a Spring Boot demo project._

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Description
This project to showcase the use of Spring Boot for a REST API; not only should it have the main functionality of a ToDo List, although it must satisfy Non-Functional Requirements like error handling, proper logging, monitoring, testing.

The ToDo functionality will be kept simple; you can CRUD Lists and their respective Tasks.

---

## Setting Up
### Prerequisites
- Java 14
- Spring Boot 2.2.7
- Maven 3.6.1
### Local Development
One of the benefits of Sprint Boot is that it comes with an embedded web server. 
Using the Maven build provided by the Spring Boot Initialzr, you'll get a .jar file inside the `/target` directory. 
You can use the `.jar` file to run the entire Spring application.
``` sh
# generates categorizer-0.0.1-SNAPSHOT.jar
mvn clean install

# runs the application using the embedded web server.
java -jar target/todo-list-api-0.0.1-SNAPSHOT.jar
```

### Run Tests
For running the tests you can type 
``` sh
mvn test
```

---

## Authors
[Gerardo Cortés Oquendo](mailto:gerardo.cortes.o@gmail.com)
