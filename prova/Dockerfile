FROM openjdk:8-jdk-alpine

COPY app.jar {container}
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","{JAR_NAME}"]