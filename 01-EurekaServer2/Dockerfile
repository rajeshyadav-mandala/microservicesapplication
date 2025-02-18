# Use OpenJDK 17 as the base image
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file into the container
COPY target/01-EurekaServer-0.0.1-SNAPSHOT.jar .

# Expose the application port
EXPOSE 4041

# Run the application
CMD ["java", "-jar", "01-EurekaServer-0.0.1-SNAPSHOT.jar"]
