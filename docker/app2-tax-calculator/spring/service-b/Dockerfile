FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY target/*.jar app.jar
EXPOSE 4000
CMD ["java","-jar","app.jar","--server.port=4000"]