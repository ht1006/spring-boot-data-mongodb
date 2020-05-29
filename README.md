### Some notes from Helen:

Changes I made that different from the original repository:

1. In 'controller/TutorialController.java', I deleted the url next to CrossOrigin which is specified to listen on localhost:8080.

1. To connect to local mongodb, in 'src/main/resources/application.properties', use 'spring.data.mongodb.database=bezkoder_db' and 'spring.data.mongodb.port=27017'.

1. To connect to the mongo instance delpoyed on Openshift, comment out the other lines and use 'spring.data.mongodb.uri=mongodb://userVL0:6Q0jw4gRVVKCOYgt@mongodb/tutorials-db'.

---

# Spring Boot MongoDB CRUD example - Restful CRUD API

For more detail, please visit:
> [Spring Boot with MongoDB CRUD example using Spring Data](https://bezkoder.com/spring-boot-mongodb-crud/)

## Run Spring Boot application
```
mvn spring-boot:run
```
