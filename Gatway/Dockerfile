FROM openjdk:17

WORKDIR /App

COPY /target/Client-0.0.1-SNAPSHOT.jar .

EXPOSE 8086

ENTRYPOINT ["java", "-jar", "Client-0.0.1-SNAPSHOT.jar"]