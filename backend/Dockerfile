FROM openjdk:11

# Installer Maven
RUN apt-get update && apt-get install -y maven

WORKDIR /app

COPY . /app

RUN mvn package

EXPOSE 8080

CMD ["java", "-jar", "target/hrm-backend-0.0.1-SNAPSHOT.jar"]

