1. For start the spring boot application externally

  java -jar target/refresh-test-0.0.1-SNAPSHOT.jar --spring.config.location=<path-of-application-properties>
  
  
2. trigger endpoint
    GET: http://localhost:8080/app-name
    
3. change the app.name in application.properties

4. For getting the reflected changes run below endpoint
    POST: http://localhost:8080/actuator/refresh

5. Re trigget the above get endpoint for getting the updated app.namep
