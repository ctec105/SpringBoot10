# SpringBoot10: Conexión a base de datos
Creando conexión a la base de datos con Hibernate

Configuración de la base de datos en el Application Porperties:

spring.datasource.url = jdbc:mysql://localhost:3306/usuarios?serverTimezone=UTC
spring.datasource.username = root
spring.datasource.password = root
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.show-sql = true
spring.jpa.hibernate.ddl-auto = update
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect

# Herramientas:
- Spring Tool Suite 4
- Spring Boot 2.3.5
- Spring Web 
- Thymeleaf
- JPA-Hibernate

