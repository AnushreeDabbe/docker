FROM java:8-jre
WORKDIR usr/src
ADD ./target/apigateway-service-0.0.1-SNAPSHOT.jar /usr/src/apigateway-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","apigateway-service-0.0.1-SNAPSHOT.jar"]
