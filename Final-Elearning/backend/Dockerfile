# Base image for Java
FROM adoptopenjdk/rapidfort/tomcat10-openjdk17-ib:alpine-jre

# Define the build artifact path as an argument
ARG artifact=target/spring-boot-web.jar

# Set the working directory inside the container
WORKDIR /opt/app

# Copy the built Spring Boot JAR file into the container
COPY ${artifact} app.jar

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
