# java-spring-simple-crud

### Build and Run via Docker

```
./mvnw clean package

docker build -t spring-demo .

docker run -p 8081:8081 spring-demo
```