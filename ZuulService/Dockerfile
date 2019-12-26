FROM java:8
ADD /target/zuul-service-0.1.jar zuul-service-0.1.jar
ENTRYPOINT ["java", "-Dspring.profiles.active=production", "-jar", "zuul-service-0.1.jar"]