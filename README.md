Spring Boot and Thymeleaf with AdminLTE
=======================================

- Spring Boot
- Web application (WAR) packaging as well as self-contained JAR
- Thymeleaf with Java 8 Time (Java8TimeDialect)
- WebJars
- Selenium configuration included
- Maven Wrapper included

```
mvn -N io.takari:maven:wrapper
```

## Run the project with

```
cd /path/to/project
./mvnw clean spring-boot:run
```

Open browser to http://localhost:8080/


## To package the project run

```
./mvnw clean package
```

Referenced articles
-------------------

- [Java 8 Date & Time with Thymeleaf](http://blog.codeleak.pl/2015/11/how-to-java-8-date-time-with-thymeleaf.html)
- [Spring Boot and Thymeleaf with Maven](http://blog.codeleak.pl/2014/04/how-to-spring-boot-and-thymeleaf-with-maven.html)
- [Spring Boot Integration Testing with Selenium](http://blog.codeleak.pl/2015/03/spring-boot-integration-testing-with.html)
