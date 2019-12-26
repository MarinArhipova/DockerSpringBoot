FROM java:8
ADD /target/cat-service-0.1.jar cat-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "cat-service-0.1.jar"]