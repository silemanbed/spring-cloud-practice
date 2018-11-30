# Spring Cloud Practice




## Getting Started

you need to create some prperties for your configuration name as below:
  
  "carservices.properties" -> for this file needs to contain "server.port=8101" or you can give any port
  
  "reservationbusinessservices.properties" -> for this file needs to contain "server.port=8500" or you can give any port

And then commit the git and give the git url for your config file to application.properties that is under config-server module.

### Prerequisites

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally

Firstly start config-server module
Secondly start Eureka-server module
Then Other services
