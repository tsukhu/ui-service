# ui-service
Spring boot + SPA client app app

One of the challenges of working with Angular 2 is to take care of things like CORS, Security, API access.
This project bundles an SPA app inside SpringBoot.Now you can leverage the Spring Boot eco-system to create a UI microservice , add discovery , Zuul API proxy , security etc.

As a sample an Angular 2 app has been dropped into the ui folder and can be replaced by any other SPA framework structure.The ui folder is based on the exact structure provided by @AngularClass in the angular2-webpack-starter project. So this give the ability for the UI dev project to continue as-is , but for production deployment it will be packaged as a Spring Boot UI microservice

## Steps
1) Install mvn , npm , java 1.8

2) Install the dependencies given in the AngularClass project https://github.com/AngularClass/angular2-webpack-starter

3) Build the app
```
mvn clean install
```
4) Run the app
```
java -jar target\ui-service-0.0.1-SNAPSHOT.jar
```
