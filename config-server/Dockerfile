FROM openjdk:17-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} config-server-0.0.1.jar
EXPOSE 9101
ENTRYPOINT ["java","-jar","/config-server-0.0.1.jar"]