# Step 1: Use official Java runtime as a base image
FROM eclipse-temurin:21-jdk


# Step 2: Set working directory inside container
WORKDIR /app

# Step 3: Copy the built JAR file into container
COPY target/*.jar app.jar

# Step 4: Expose port 8085
EXPOSE 8085

# Step 5: Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]

