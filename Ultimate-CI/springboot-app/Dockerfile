# Base image 
FROM openjdk:11

WORKDIR /opt/app

COPY target/*.jar app.jar

ENTRYPOINT ["java","-jar","app.jar"]
