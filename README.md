# testeFullStack

Getting Started
Reference Documentation
For further reference, please consider the following sections:

Official Apache Maven documentation
Spring Boot Maven Plugin Reference Guide
Create an OCI image
Spring Web
Spring Boot DevTools
Spring Data JDBC
Spring Data JPA
Validation
Spring Boot Actuator
codecentric's Spring Boot Admin (Client)
Cloud Bootstrap
Guides
The following guides illustrate how to use some features concretely:

Building a RESTful Web Service
Serving Web Content with Spring MVC
Building REST services with Spring
Using Spring Data JDBC
Accessing Data with JPA
Validation
Building a RESTful Web Service with Spring Boot Actuator
Maven Parent overrides
Due to Maven's design, elements are inherited from the parent POM to the project POM. While most of the inheritance is fine, it also inherits unwanted elements like <license> and <developers> from the parent. To prevent this, the project POM contains empty overrides for these elements. If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.
