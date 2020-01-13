FROM java:8
ARG JAR_FILE=target/zuul-service-0.1.jar
ADD ${JAR_FILE} zuul-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "zuul-service-0.1.jar"]