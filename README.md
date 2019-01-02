# RESTFUL-Spring-Microservice
A lightweight RESTful spring microservice using JWT for authentication, eureka for service discovery and load balancing, and cassandra for storage.

### Building
This project uses the gradle wrapper as it's build tool. For windows users, run `gradlew.bat build` from the command line to build the project. For linux users,
run the gradlew executable `./gradlew build`. 

### Running the registry and microservice
First run the eureka registry server jar file which should be located under `RESTFUL-Spring-Microservice\eureka-service-registry\build\libs` using `java -jar eureka-service-registry-0.0.1-SNAPSHOT`.
Second, run the rest microservice jar located under `RESTFUL-Spring-Microservice\rest-microservice\build\libs using` `java -jar rest-microservice-0.0.1-SNAPSHOT`.
Visit (http://localhost:8080/service-instances/test-registry) to view both services in action.
