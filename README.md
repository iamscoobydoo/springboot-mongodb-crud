# springboot-mongodb-crud
Demo application built on SpringBoot and MongoDB

## APIs
The server runs on Tomcat, on <http://localhost:8080>
Route                        | METHOD | Description
---------------------------- | ------ | -------------
/api/tutorials               | GET    | Get all tutorials
/api/tutorials/:tutorial_id  | GET    | Get tutorial data by id
/api/tutorials/published     | GET    | Get all published tutorials
/api/tutorials               | POST   | Add a new tutorial data
/api/tutorials?id            | PUT    | Update tutorial
/api/tutorials/:tutorial_id  | DELETE | Delete tutorial data by id
/api/tutorials               | DELETE | Delete all tutorials

## Dependencies
* [Spring Boot Starter Web](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-web)
* [Spring Boot MongoDB](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-data-mongodb)
* [Spring Boot Validation](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation)
