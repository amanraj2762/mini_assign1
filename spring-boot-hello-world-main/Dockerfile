FROM openjdk:17-jdk-slim
WORKDIR /aman
COPY target/hello-world-1.0.2-SNAPSHOT.jar /aman/helloworld-java.jar
EXPOSE 8085
CMD ["java", "-jar", "/aman/helloworld-java.jar"]
