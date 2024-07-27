FROM openjdk:11
WORKDIR /app
COPY . /app
RUN ./mvnw package
EXPOSE 8080
CMD ["java", "-jar", "target/hrm-backend-0.0.1-SNAPSHOT.jar"]

