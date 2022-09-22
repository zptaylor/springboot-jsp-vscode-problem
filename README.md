# GitHub Help Request for JSP Spring boot project

This is an example project that illustrates an issue with the default launch.json behavior for a specific use case involving JAR files, created in Maven, that have Spring Boot and JSP.

The issue: when running in Debug mode in VSCode, and going to the URL http://localhost:8080/ , an Error page is displayed.

The project runs correctly when you go to the terminal manually and type:

- java -jar .\target\boot-exploded-jar-webapp-1.0-SNAPSHOT.jar

Is there a particular VM argument that can be overridden that would fix this behavior?
