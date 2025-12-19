# Point of Sale Application

A Spring Boot application for Point of Sale management.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Build

```bash
cd POV-JAVA
mvn clean install
```

## Run

```bash
mvn spring-boot:run
```

Or run the JAR file:

```bash
java -jar target/Point-of-sale-0.0.1-SNAPSHOT.jar
```

## Docker

Build the Docker image:

```bash
docker build -t point-of-sale .
```

Run the container:

```bash
docker run -p 8080:8080 point-of-sale
```

## Project Structure

```
POV-JAVA/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/Point/of/sale/
│   │   │       ├── PointOfSaleApplication.java
│   │   │       └── controller/
│   │   │           └── HelloController.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/example/Point/of/sale/
│               └── PointOfSaleApplicationTests.java
├── Dockerfile
└── pom.xml
```

## License

This project is licensed under the MIT License.
