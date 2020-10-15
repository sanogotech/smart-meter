FROM openjdk:8-jdk-alpine
# MAINTAINER Taner Diler <taner.diler@gmail.com>
ADD target/gateway-1.0.0.jar  gateway.jar
ENTRYPOINT ["java", "-jar", "/gateway.jar"]
EXPOSE 8080
