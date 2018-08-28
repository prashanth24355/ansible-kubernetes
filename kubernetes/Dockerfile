FROM openjdk:8

MAINTAINER Udit

ADD weather-1.0-SNAPSHOT.jar weather-1.0-SNAPSHOT.jar
ADD config.yml config.yml
EXPOSE 8080

CMD ["java", "-jar", "weather-1.0-SNAPSHOT.jar", "server", "config.yml"]