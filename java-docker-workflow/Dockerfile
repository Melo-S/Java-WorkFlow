FROM openjdk:8-jdk-alpine
COPY . /app
WORKDIR /app
RUN ./gradlew build
CMD ["java", "-jar", "build/libs/java-docker-workflow-1.0-SNAPSHOT.jar"]
