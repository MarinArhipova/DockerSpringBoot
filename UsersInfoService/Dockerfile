FROM java:8
ARG JAR_FILE=target/users-info-service-0.1.jar
ADD ${JAR_FILE} users-info-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "users-info-service-0.1.jar"]