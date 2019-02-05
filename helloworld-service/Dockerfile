FROM openjdk:8-jre-alpine
COPY ./target/helloworld-service*.jar /opt/app.jar
WORKDIR /opt
CMD ["java","-jar","/opt/app.jar"]
