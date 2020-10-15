FROM openjdk:8-jdk-alpine
# MAINTAINER Taner Diler <taner.diler@gmail.com>
ADD target/\service-registry-1.0.0.jar service-registry.jar
ENTRYPOINT ["java", "-jar", "/service-registry.jar"]
EXPOSE 8761
