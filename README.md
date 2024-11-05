# Spring Boot Greeting Application

A simple Spring Boot application that provides a `GET` endpoint to greet users by name.

## Features

- A REST API endpoint `/greeting` that returns a greeting message.
- Accepts an optional `name` parameter to personalize the greeting.

## Requirements

- Java 11 or higher
- Maven 3.6+ or Gradle
- Spring Boot 2.5+ (Included in dependencies)

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ashishjsharda/SpringBootBasicGetDemo.git
cd SpringBootBasicGetDemo
```

### 2. Build and Run the Application

#### Using Maven

```bash
./mvnw spring-boot:run
```

#### Using Gradle

```bash
./gradlew bootRun
```

### 3. Access the Endpoint
Once the application is running, open a browser or use a tool like curl to access the endpoint.

*   **Default Greeting**: http://localhost:8080/greeting**Response**: Hello, World!

*   **Personalized Greeting**: http://localhost:8080/greeting?name=Ashish**Response**: Hello, Ashish!
