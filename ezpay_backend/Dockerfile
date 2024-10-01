# Use an official Java runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the jar file from the target directory into the container
COPY target/backend-0.0.1-SNAPSHOT.jar app.jar

# Expose the port your application runs on
EXPOSE 8090
# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
