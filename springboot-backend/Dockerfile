FROM openjdk:17-alpine

WORKDIR /app

COPY target .

EXPOSE 8080

ENTRYPOINT ["java"]

CMD ["-jar", "springboot-backend-0.0.1-SNAPSHOT.jar"]