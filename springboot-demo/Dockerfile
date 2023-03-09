FROM openjdk:17-alpine
VOLUME /main-app
ADD target/springboot.jar springboot.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar","/springboot.jar"]