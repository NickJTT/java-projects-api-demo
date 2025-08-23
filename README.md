# java-projects-api-demo
A simple Java Spring Boot project bootstrapped by Maven and using PostgreSQL with Hibernate

# Starting the project
`docker container run -p 5432:5432 --name pg -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -e POSTGRES_DB=project -d postgres`

`mvn clean compile`

`mvn spring-boot:run`
