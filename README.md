# Springboot DDD (Domain Driven Design) Web Starter Kit

## Application properties
Application properties, `application.yml` or `application.properties`, is configured in `/configuration/src/main/resources`.

## How to start the application
1. Run `mvn clean package` to build your application.
2. Start application with `mvn spring-boot:run -pl configuration` or `java -jar configuration/target/springboot-ddd-web-starter-kit-{version}.jar`
    * Additional environment property can be added to change active profiles `--spring.profiles.active={profile}`
    * You can also refer to an explicit location using the **spring.config.location** environment property (comma-separated list of directory locations, or file paths). `--spring.config.location=/path/to/application.properties`
