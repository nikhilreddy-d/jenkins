FROM amazoncorretto:17-alpine-jdk
LABEL AUTHOR="nikhil"
COPY /target/spring-petclinic-3.2.0-SNAPSHOT.jar /spring-petclinic.jarEXPOSE 8080
ENTRYPOINT ["java", "-jar"]
CMD ["/spring-petclinic.jar"]