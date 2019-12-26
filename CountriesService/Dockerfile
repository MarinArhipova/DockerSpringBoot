FROM java:8
ADD /target/countries-service-0.1.jar countries-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "countries-service-0.1.jar"]