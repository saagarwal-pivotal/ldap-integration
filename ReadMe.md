# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/maven-plugin/)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#boot-features-developing-web-applications)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#production-ready)
* [Spring LDAP](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/htmlsingle/#boot-features-ldap)
* [Embedded LDAP Server](https://docs.spring.io/spring-boot/docs/2.2.0.RELEASE/reference/html/boot-features-nosql.html#boot-features-ldap-embedded)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)
* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)


### Embedded ldap   

All users are loaded in embedded ldap.
Users who have developer group assigned will have access to developer end points
Refer to WebSecurityConfig file
Authenication logic example too is demonstrated in the same file
PersonRepository has an example usage for ldapTemplate 


