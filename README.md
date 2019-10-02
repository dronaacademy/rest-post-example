## REST POST Example

This project demonstrates how spring boot rest web services can be used to save data to the database by exposing POST methods. This is the backend application.

### Prerequisites

* Java 8 or above
* Apache Maven
* MySQL Server

### Build instructions

```
mvn clean install -DskipTests
```

### Execution Instructions

```
mvn spring-boot:run
```

### Notes

* Please make sure that you modify the application.properties files to reflect your database properties.
* The database password in application.properties shows as plain text. This is not the way you code for production. Please use Jasypt or any other encryption mechanism to encrypt the password.
* Cross Origin Requests from localhost are allowed in this application so that an angular application running in your localhost can call these services.