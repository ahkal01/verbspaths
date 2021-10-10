
## Running unit and integration tests

To run the unit and integration tests:

    cd verbs-paths-from-swagger
    mvnw test
    
## Building the JAR

    mvnw package

## Starting the service

JRE 11 is required to run the service.
The service can be started with:

    cd target
    java -jar verbspaths-0.0.1-SNAPSHOT.jar

## Using the service with Swagger UI

Open a browser to:

    http://localhost:8080/verbs-paths/swagger-ui.html
    
Expand:

    GET /verbs-paths
    
Click on Try it out and enter the URL to the Swagger file to analyse e.g.

    https://petstore.swagger.io/v2/swagger.json
    
    file:c:/testdata/sample.json
    
