FROM openjdk:17-alpine
VOLUME /main-app
ADD target/springbootassignment.jar springbootassignment.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar","/springbootassignment.jar"]