FROM java:8
ARG JAR_FILE=target/service-registry-0.1.jar
ADD ${JAR_FILE} service-registry-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "service-registry-0.1.jar"]