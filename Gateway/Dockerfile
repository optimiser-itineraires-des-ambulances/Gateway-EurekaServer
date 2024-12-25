FROM openjdk:21
VOLUME /tmp
ADD target/gateway-docker.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]