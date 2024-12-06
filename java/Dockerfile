FROM openjdk:8-jre-alpine

WORKDIR /usr/src/app

COPY target/java-0.0.1-SNAPSHOT.jar .

LABEL maintainer="baptiste"

EXPOSE 8448

CMD ["java", "-jar", "java-0.0.1-SNAPSHOT.jar"]

