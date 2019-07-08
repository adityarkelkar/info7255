# Advanced Big Data Applications and Indexing Techniques
## Northeastern University (May 2019 - August 2019)

Repository related to development for REST Api prototype model demo work for INFO 7255

## Contents
In this project, we will develop a REST Api to parse a JSON schema model divided into three demos
1. **Prototype demo 1**
    - Develop a Spring Boot based REST Api to parse a given sample JSON schema.
    - Save the JSON schema in a redis key value store.
    - Demonstrate the use of operations like `GET`, `POST` and `DELETE` for the first prototype demo.
2. **Prototype demo 2**
    - Regress on your model and perform additional operations like `PUT` and `PATCH`.
    - Secure the REST Api with a security protocol like JWT or OAuth2.

## Running the prototype

### Pre-requisites
1. Java
2. Maven
3. OAuth 2.0 client (Refer Google APIs for more details)

### Build & Test
```
mvn clean install
```

### Run as Spring Boot application
1. Method 1 (**Recommended**)  
```
mvn spring-boot:run -Dsecurity.oauth2.client.clientId=<CLIENT_ID> -Dsecurity.oauth2.client.clientSecret=<CLIENT_SECRET>
```
2. Method 2  
```
Set the security credentials in `application.properties` file in the project resources
```