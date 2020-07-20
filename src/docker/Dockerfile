FROM openjdk:8-jdk
VOLUME /tmp
ARG JAR_FILE
COPY ${JAR_FILE} vithi.jar
ENTRYPOINT ["java", "-jar", "/vithi.jar"]