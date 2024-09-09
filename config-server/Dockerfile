FROM openjdk:22-jdk

WORKDIR /app

COPY target/config-server-0.0.1-SNAPSHOT.war /app/config-server.war

CMD ["java", "-jar", "config-server.war"]