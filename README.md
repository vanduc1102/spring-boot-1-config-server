# spring-boot-1-config-server
Configuration Server

This project loads configuration from: [https://github.com/vanduc1102/spring-boot-1-config-repos](https://github.com/vanduc1102/spring-boot-1-config-repos)

# Running development

`./mvnw spring-boot:run`

# Running production

`java -jar target/config-server-0.0.1-SNAPSHOT.jar`


# Checking URLs

[http://localhost:8888/](http://localhost:8888/)

[http://localhost:8888/application-local.properties](http://localhost:8888/application-local.properties)

[http://localhost:8888/ecatalog-composite-local.yml](http://localhost:8888/ecatalog-composite-local.yml)

[http://localhost:8888/spring-cloud-config-client-local.properties](http://localhost:8888/spring-cloud-config-client-local.properties)

## Reading detail configuration

[http://localhost:8888/spring-cloud-config-client/local](http://localhost:8888/spring-cloud-config-client/local)
