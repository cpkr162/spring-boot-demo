# spring-boot-demo
Demo project for Spring Boot

# Build the spring boot application
mvn clean install

# Skip test cases
mvn clean install -Dmaven.test.skip=true

# Start the spring boot application
java -Dserver.port=8181 -jar  demo-0.0.1-SNAPSHOT.jar

# Test the GET Welcome/Default service 
curl http://localhost:8181/