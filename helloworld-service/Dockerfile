FROM openjdk
COPY ./helloworld-service/target/helloworld-service*.jar /opt/app.jar
WORKDIR /opt
CMD ["java","-jar","/opt/app.jar"]
