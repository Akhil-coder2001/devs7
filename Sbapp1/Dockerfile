# Use a lightweight OpenJDK image
FROM openjdk

# Set working directory
WORKDIR /app1

# Copy the built JAR file into the container
COPY target/*.jar/app1.jar


# Command to run the Spring Boot app
CMD ["java", "-jar", "Dockerapp1.jar"]
