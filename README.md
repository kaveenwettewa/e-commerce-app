# E-Commerce Web Application

A full-stack e-commerce web application built with Java Spring Boot, Thymeleaf, and H2 database.

## Features

- User registration and login
- Product browsing and searching
- Shopping cart functionality
- Checkout process
- Payment processing
- Order management
- Product recommendations
- Responsive design

## Technologies Used

- **Backend**: Java Spring Boot
- **Frontend**: Thymeleaf, Bootstrap 5, HTML, CSS, JavaScript
- **Database**: H2 Database (in-memory)
- **Security**: Spring Security
- **Build Tool**: Maven

## Project Structure

```
ecommerce-app/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── ecommerce/
│   │   │           ├── config/
│   │   │           ├── controller/
│   │   │           ├── model/
│   │   │           ├── repository/
│   │   │           ├── security/
│   │   │           ├── service/
│   │   │           └── EcommerceApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── css/
│   │       │   ├── js/
│   │       │   └── images/
│   │       ├── templates/
│   │       ├── application.properties
│   │       └── data.sql
│   └── test/
└── pom.xml
```

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Run the application using Maven:

```bash
mvn spring-boot:run
```

4. Open your browser and go to `http://localhost:8080`

## Default Users

The application comes with two pre-configured users:

1. **Admin User**
   - Username: admin
   - Password: admin123
   - Role: ADMIN

2. **Regular User**
   - Username: user
   - Password: user123
   - Role: USER

## Database

The application uses an H2 in-memory database for development purposes. You can access the H2 console at `http://localhost:8080/h2-console` with the following credentials:

- JDBC URL: `jdbc:h2:mem:ecommercedb`
- Username: `sa`
- Password: `password`

## License

This project is licensed under the MIT License.
