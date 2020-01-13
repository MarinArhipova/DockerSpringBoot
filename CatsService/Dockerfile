FROM java:8
ARG JAR_FILE=target/cat-service-0.1.jar
ADD ${JAR_FILE} cat-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "cat-service-0.1.jar"]