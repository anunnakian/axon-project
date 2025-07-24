# Axon Project

This repository demonstrates a simple multi-module Maven setup using the [Axon Framework](https://axoniq.io/).

## Modules

- **module1** – a minimal Spring Boot application that depends on Axon.
- **module2** – another simple Spring Boot application with the same dependency.

The Axon dependency is declared via the Maven coordinates:

```xml
<dependency>
    <groupId>org.axonframework</groupId>
    <artifactId>axon-spring-boot-starter</artifactId>
    <version>${axon.version}</version>
</dependency>
```

Build the project with:

```bash
mvn package
```
