FROM openjdk:22-jdk

WORKDIR /app

COPY target/API-Gateway-0.0.1-SNAPSHOT.war /app/API-gateway.war

CMD ["java", "-jar", "API-gateway.war"]