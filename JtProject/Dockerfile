FROM openjdk:17-jdk-slim
WORKDIR /app

# Copy the JAR from target folder into container
COPY target/ecommjava-1.0.jar app.jar

# Expose the port Spring Boot runs on
EXPOSE 8081

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
