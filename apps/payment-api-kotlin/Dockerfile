FROM gradle:7.6.0-jdk17
WORKDIR /app
COPY . .
RUN gradle build
CMD ["java", "-jar", "build/libs/app.jar"]
