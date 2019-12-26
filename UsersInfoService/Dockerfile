FROM java:8
ADD /target/users-info-service-0.1.jar users-info-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "users-info-service-0.1.jar"]