FROM eclipse-temurin:11-jre

WORKDIR /opt/app

ARG artifact=target/spring-boot-web.jar

COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
