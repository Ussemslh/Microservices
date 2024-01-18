FROM openjdk:17

WORKDIR /App

COPY /target/Eureka_server-0.0.1-SNAPSHOT.jar .

EXPOSE 8086

ENTRYPOINT ["java", "-jar", "Eureka_server-0.0.1-SNAPSHOT.jar"]