# Step 1: Use Java 17 JDK base image
FROM eclipse-temurin:17-jdk-alpine

# Step 2: Set working directory inside container
WORKDIR /app

# Step 3: Copy Spring Boot JAR from target folder into container
COPY target/*.jar app.jar

# Step 4: Expose the port your Spring Boot app runs on
EXPOSE 8080

# Step 5: Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "app.jar"]
