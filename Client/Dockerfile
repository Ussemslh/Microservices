FROM openjdk:17

WORKDIR /App

COPY /target/Gatway-0.0.1-SNAPSHOT.jar .

EXPOSE 8086

ENTRYPOINT ["java", "-jar", "Gatway-0.0.1-SNAPSHOT.jar"]