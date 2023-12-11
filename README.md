# Postgres_Springboot

# Resources
````
spring.datasource.url=jdbc:postgresql://localhost:5432/NOME_DO_BANCO_DE_DADOS
spring.datasource.username=usuario
spring.datasource.password=senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.jdbc.lab.non_contextual_creation=true
````
# POM.XML
```
<dependency>
    <groupId>org.postgresql</groupId>
    <artifactId>postgresql</artifactId>
    <scope>runtime</scope>
</dependency>
```
