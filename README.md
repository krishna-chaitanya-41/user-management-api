# User Management API

RESTful User Management API built using Spring Boot with layered architecture and exception handling.

## Features

* CRUD Operations for Users
* RESTful API Endpoints
* Layered Architecture (Controller → Service → Repository)
* Global Exception Handling
* Spring Boot Configuration
* Database Integration using Spring Data JPA

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* Maven
* PostgreSQL
* REST APIs

## Project Structure

```bash
src/main/java/com/example/usermanagement/api
│
├── config
├── controller
├── exception
├── model
├── repository
├── service
```

## API Endpoints

| Method | Endpoint    | Description          |
| ------ | ----------- | -------------------- |
| GET    | /users      | Get all users        |
| GET    | /users/{id} | Get user by ID       |
| POST   | /users      | Create new user      |
| PUT    | /users/{id} | Update existing user |
| DELETE | /users/{id} | Delete user          |

## Setup Instructions

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project directory

```bash
cd user-management-api
```

3. Configure database credentials in `application.properties`

4. Run the application

```bash
./mvnw spring-boot:run
```

## Testing

API endpoints can be tested using Postman.

## Author

Kalikota Krishna Chaitanya
