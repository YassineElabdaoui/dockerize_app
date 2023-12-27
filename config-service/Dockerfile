FROM openjdk:17-oracle
VOLUME /tmp
COPY ./target/* app.jar
ENTRYPOINT ["java","-jar","app.jar"]
