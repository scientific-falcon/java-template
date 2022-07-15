FROM openjdk:8-jre-alpine
WORKDIR /app
COPY target/my-web-app.jar ./
EXPOSE 8080
ENTRYPOINT java $SYS_PROPS -jar my-web-app.jar
