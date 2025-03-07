# 🔐 JWT Authentication with Spring Boot

**JWT Authentication** is a Spring Boot application that demonstrates how to implement JSON Web Token (JWT) based authentication using Spring Security. This approach provides a stateless, efficient, and secure method for authenticating users in a web application.

## 📌 Features

- **User Authentication**: Secure login mechanism using JWTs.
- **Role-Based Authorization**: Access control based on user roles.
- **Stateless Sessions**: Eliminates the need for server-side session storage.
- **RESTful API Endpoints**: Secure APIs with token-based authentication.

## 🏗️ Project Structure

```
JwtAuthentication/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── jwtauthentication/
│   │   │               ├── config/          # Security configurations
│   │   │               ├── controller/      # REST controllers
│   │   │               ├── model/           # Entity models
│   │   │               ├── repository/      # Data repositories
│   │   │               ├── security/        # JWT utilities and filters
│   │   │               └── service/         # Business logic
│   └── resources/
│       ├── application.properties           # Application configurations
│── .gitignore
│── mvnw
│── mvnw.cmd
│── pom.xml
```

## ⚡ Tech Stack

- **Java**: Programming language.
- **Spring Boot**: Application framework.
- **Spring Security**: Security framework.
- **JWT**: JSON Web Tokens for authentication.
- **Maven**: Build and dependency management.

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/HarshKadbe/JwtAuthentication.git
cd JwtAuthentication
```

### 2️⃣ Build the Project

```bash
./mvnw clean install
```

### 3️⃣ Run the Application

```bash
./mvnw spring-boot:run
```

### 4️⃣ Test the Endpoints

Use tools like Postman or curl to test the authentication endpoints:

- **Register**: `POST /api/auth/register`
- **Login**: `POST /api/auth/login`
- **Access Secured Endpoint**: `GET /api/user/profile` (requires JWT)

## 🛡️ Security Implementation

- **JWT Tokens**: Used for stateless authentication.
- **Spring Security Filters**: Process and validate JWTs.
- **Password Encoding**: Secure storage of user passwords.

## 🏗️ Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
