# User Management System

This is a simple User Management System built with Spring Boot that allows you to perform CRUD (Create, Read, Update, Delete) operations on user data.

## Features

- Create new users with first name and last name
- Find users by first name
- Update existing user information
- Delete users from the system
- Modern and responsive user interface

## Technologies Used

- Spring Boot
- Spring Data JPA
- H2 Database
- Thymeleaf templating engine
- HTML5 & CSS3

## Getting Started

### Prerequisites

- Java JDK 11 or later
- Maven

### Running the Application

1. Clone this repository
2. Navigate to the project directory
3. Run the following command:
   ```bash
   mvn spring-boot:run
   ```
4. Open your browser and visit `http://localhost:8080`

## API Endpoints

- `POST /register` - Create a new user
- `GET /user` - Find user by first name
- `POST /user/update` - Update user information
- `POST /user/delete` - Delete a user

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── gpt/
│   │       └── frist/
│   │           ├── FristApplication.java
│   │           ├── User.java
│   │           ├── UserController.java
│   │           └── UserRepository.java
│   └── resources/
│       ├── static/
│       │   └── css/
│       │       └── style.css
│       ├── templates/
│       │   ├── index.html
│       │   └── welcome.html
│       └── application.properties
```

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.