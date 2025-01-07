
#Base Image for java
FROM adoptopenjdk/openjdk11:x86_64-alpine-jre-11.0.5_10

#simply the artifact path
ARG artifact=target/ELearningManagement-0.0.1-SNAPSHOT.jar

WORKDIR /app

COPY ${artifact} /app/app.jar


#Set the default command to run the Java application when the container starts
ENTRYPOINT ["java","-jar","/app/app.jar"]