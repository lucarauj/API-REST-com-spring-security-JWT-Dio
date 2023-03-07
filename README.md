[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/LICENSE)

<h1 align="center"> API REST</h1>
<h2 align="center"> Com Spring Security e JWT </h2>

<p align="center"><img width="450px" src="https://github.com/lucarauj/assets/blob/main/SpringSecurity.png" /></p>


### ⛏ Criação do projeto base com as seguintes dependências:

- Web
- Spring Security
- Spring Data JPA
- H2 Database

- JWT 👇
```
<dependency>
	<groupId>io.jsonwebtoken</groupId>
	<artifactId>jjwt</artifactId>
	<version>0.7.0</version>
</dependency>
```

### ❌ Gerando o Projeto no [Spring.io](https://start.spring.io/):

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/spring.io.png"/>

<br>

### ✅ Tela de Login do Spring Security:

<img width="500px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/tela.security.png"/>

<br>

### ⚙ Configurando o arquivo ```application.properties``` :

```
security.config.prefix=Bearer
security.config.key=SECRET_KEY
security.config.expiration=3600000

spring.jpa.database-plataform=org.hibernate.dialect.H2Dialect
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=sa
spring.jpa.show-sql:true
spring.h2.console.enabled=true
```

## ❌ Utilizando o Posman:

<br>

- ## Cadastrar Usuário:

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/cadastrarUsuario.png"/>

<br>

- ## Efetuar Login:

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/efetuarLogin.png"/>

<br>

- ## Acesso autorizado - Rota Users - via Token:

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/authorizedUser.png"/>

<br>

- ## Acesso autorizado - Rota Users - via Token:

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/authorizedUser.png"/>

<br>

- ## Acesso autorizado - Rota Managers - via Token/Headers:

<img width="900px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/authorizedManagerHeader.png"/>

<br>

- ## Debugger do Token gerado no [JWT.io](https://jwt.io/):

<img width="800px" src="https://github.com/lucarauj/API-REST-com-spring-security-JWT-Dio/blob/main/image/debuggerJwt.png"/>

<br>


### 📝 Anotações:

- @Autowired
- @Bean
- @Configuration
- @ConfigurationProperties
- @Column
- @CollectionTable
- @EnableWebSecurity
- @EnableGlobalMethodSecurity(prePostEnabled = true)
- @Entity
- @ElementCollection
- @GeneratedValue
- @Id
- @JoinColumn
- @Param
- @PostMapping
- @Query
- @RestController
- @RequestMapping
- @RequestBody
- @Service
- @Table

<br>

### 🚀 Principais tecnologias utilizadas no projeto:

<div style="display: inline_block"><br>
<img align="center" alt="Lucarauj-Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
<img align="center" alt="Lucarauj-Postman" height="50" width="90" src="https://github.com/lucarauj/assets/blob/main/postman.png">
<img align="center" alt="Lucarauj-Spring" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg">
<img align="center" alt="Lucarauj-SpringBoot" height="40" width="110" src="https://github.com/lucarauj/assets/blob/main/SpringBoot.jpeg">
<img align="center" alt="Lucarauj-Maven" height="50" width="60" src="https://github.com/lucarauj/assets/blob/main/Maven-Apache.svg">
<img align="center" alt="Lucarauj-H2" height="30" width="30" src="https://github.com/lucarauj/assets/blob/main/H2.png">
</div>

<br>

## Autor

#### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>
