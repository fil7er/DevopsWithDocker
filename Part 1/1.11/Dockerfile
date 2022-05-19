FROM openjdk:18.0.1

WORKDIR /usr/src/app
EXPOSE 8080

COPY . .
RUN ./mvnw package

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]