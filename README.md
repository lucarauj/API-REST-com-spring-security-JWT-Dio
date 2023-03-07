# API-REST-com-spring-security-JWT-Dio

Dependências:

Web
Spring Security
Spring Data JPA
H2 Database

JWT:
```
<dependency>
	<groupId>io.jsonwebtoken</groupId>
	<artifactId>jjwt</artifactId>
	<version>0.7.0</version>
</dependency>
```

Application.properties:

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

Anotações:

@Entity
@Table
@Id
@GeneratedValue
@Column
@ElementCollection
@CollectionTable
@JoinColumn
@Query
@Param
@Service
@Autowired
@RestController
@RequestMapping
@PostMapping
@RequestBody
@Configuration
@ConfigurationProperties
@EnableWebSecurity
@EnableGlobalMethodSecurity(prePostEnabled = true)
@Bean
