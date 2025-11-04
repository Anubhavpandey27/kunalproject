FROM openjdk:17-jdk-slim
VOLUME /tmp
EXPOSE 8080

LABEL maintainer=""
LABEL version="1.0"
LABEL description=""

ARG JAR_FILE=target/masterbazzarindia-0.0.1-SNAPSHOT.jar

ADD ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","/app.jar"]
