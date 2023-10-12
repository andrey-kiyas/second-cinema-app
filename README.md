# "Second cinema app" ;)

---
The project was created for practice in going through the full cycle
from creating an empty project in the IDE to filling it to GitHub.

---
### Project endpoints:
POST: /register - all  
GET: /cinema-halls - user/admin  
POST: /cinema-halls - admin  
GET: /movies - user/admin  
POST: /movies - admin
GET: /movie-sessions/available - user/admin  
POST: /movie-sessions - admin  
PUT: /movie-sessions/{id} - admin  
DELETE: /movie-sessions/{id} - admin  
GET: /orders - user  
POST: /orders/complete - user  
PUT: /shopping-carts/movie-sessions - user  
GET: /shopping-carts/by-user - user  
GET: /users/by-email - admin  
---
### Technologies
- Java 17
- Spring Boot, Spring Security, Spring data JPA
- REST, Mapstruct
- MySQL, Liquibase
- Maven, Docker
- Lombok, Swagger
- Junit, Mockito, testcontainers
---
