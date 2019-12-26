FROM java:8
ADD /target/service-registry-0.1.jar service-registry-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "service-registry-0.1.jar"]