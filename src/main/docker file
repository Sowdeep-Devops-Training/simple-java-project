FROM openjdk:17-jdk-alpine
WORKDIR /src/app
COPY target/works-with-heroku-1.0.jar
EXPOSE 9080
CMD ["java", "-jar", "works-with-heroku-1.0.jar"]
