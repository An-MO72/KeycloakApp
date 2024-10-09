# Keycloak Spring Boot Integration

## Description

This project demonstrates the integration of Keycloak, an open-source identity and access management solution, with a Spring Boot application. It provides a secure RESTful API that leverages Keycloak for user authentication and authorization. Users can access different endpoints based on their assigned roles, allowing for a role-based access control mechanism.

## Getting Started

To start working on this project, follow these steps:

### Clone the Repository:

```bash
git clone https://github.com/An-MO72/KeycloakApp.git
cd KeycloakApp
```
## Set Up Keycloak:

- Ensure you have a Keycloak server running. You can use the Docker command provided in the project setup [guide](https://medium.com/@Mo72/keycloak-integration-with-spring-boot-11c7ed448ffd) .
- Access the Keycloak admin console at [http://localhost:8080/auth](http://localhost:8080/auth) and log in with your admin credentials.
- Create a realm and configure clients and roles as specified in the project guide.

## Configure the Spring Boot Application:

- Open the project in IntelliJ IDEA (or your preferred IDE).
- Update the `application.properties` file with your Keycloak configuration.

## Run the Application:

run the application from the IDE you use.

- The application will run on [http://localhost:8081](http://localhost:8081).

## Testing the API:

- Use Postman to obtain a user token by sending a POST request to the Keycloak token endpoint.
- Access secured API endpoints using the obtained token, and test the role-based access control by using different user credentials.

## Conclusion

This project serves as a comprehensive example of integrating Keycloak with a Spring Boot application to implement secure authentication and authorization for RESTful APIs. You can further customize and expand the project based on your requirements.
