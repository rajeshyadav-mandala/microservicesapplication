FROM openjdk:17

WORKDIR /app

COPY ./target/01-EurekaServer-0.0.1-SNAPSHOT.jar /app

EXPOSE 4041

ENTRYPOINT ["java", "-jar", "01-EurekaServer-0.0.1-SNAPSHOT.jar"]