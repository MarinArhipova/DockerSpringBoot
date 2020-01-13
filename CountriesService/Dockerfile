FROM java:8
ARG JAR_FILE=target/countries-service-0.1.jar
ADD ${JAR_FILE} countries-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "countries-service-0.1.jar"]