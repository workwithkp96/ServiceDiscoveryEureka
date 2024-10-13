**Spring Boot Service Discovery with Eureka**
**Overview**
This project is a Spring Boot application that demonstrates how to implement service discovery using Netflix Eureka. 
The application registers itself as a client with the Eureka server and enables communication with other registered microservices.

**Features**
Eureka Server: Acts as a service registry for microservices.
Eureka Client: Automatically registers the service with the Eureka server and discovers other services. Github link : https://github.com/workwithkp96/EurekaClient
Blocking Communication: Uses RestTemplate for synchronous HTTP calls to communicate with other services.
Load Balancing: Uses Spring Cloud Load Balancer to distribute requests among service instances.


**Prerequisites**
Java 11 or later
Maven
Spring Boot (version compatible with Spring Cloud)
Eureka Server (ensure it is running and accessible)
