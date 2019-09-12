FROM openjdk:8
EXPOSE 8085
ADD taskmanager-backend-0.0.1-SNAPSHOT.jar taskmanager-backend-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "taskmanager-backend-0.0.1-SNAPSHOT.jar"]
RUN sh -c 'touch /taskmanager-backend-0.0.1-SNAPSHOT.jar'