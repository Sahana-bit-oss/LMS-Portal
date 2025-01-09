
#Base Image for java
FROM openjdk:19-jdk

#simply the artifact path
#ARG artifact=target/ELearningManagement-0.0.1-SNAPSHOT.jar
#
#WORKDIR /app
#
#COPY ${artifact} /app.jar

COPY target/lms-portal.jar .

EXPOSE 8080

#Set the default command to run the Java application when the container starts
ENTRYPOINT ["java","-jar","lms-portal.jar"]