FROM openjdk:8u151-jdk-alpine3.7

ENV APP_HOME=/usr/src/app
WORKDIR $APP_HOME

COPY shopping-cart-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java","-jar","app.jar"]
