FROM openjdk:22-jdk

WORKDIR /app

COPY target/shopping-cart-service-0.0.1-SNAPSHOT.war /app/shopping-cart-service.war

CMD ["java", "-jar", "shopping-cart-service.war"]