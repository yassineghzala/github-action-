FROM eclipse-temurin:11
VOLUME /tmp
EXPOSE 8081
# ARG JAR_FILE=target/demo-0.0.1.jar
ADD ./target/*.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
