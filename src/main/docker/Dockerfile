FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD hello.jar hello.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/hello.jar"]