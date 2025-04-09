## **☕ Autenticação com JWT & OAuth em Java (Spring)**  
**Stack sugerida:**  
- **Spring Boot 3** + Spring Security.  
- **Banco de dados**: PostgreSQL.  
- **OAuth2**: Login com Google/GitHub.  
- **Redis**: Para invalidar tokens (opcional).  

### **Features obrigatórias:**  
1. Registro/login com **JWT** (rote `/auth/signup`, `/auth/login`).  
2. Rota protegida (ex: `/profile` que requer token válido).  
3. **Refresh token** (para renovar o JWT sem relogar).  

### **Features diferenciais:**  
- **Testes unitários** com JUnit/Mockito.  
- **Swagger** para documentação da API.  
- **Login social** (OAuth2 com Google).  

### **Exemplo de README:**  
```markdown
# 🔐 Authentication API  
API de autenticação com JWT + OAuth2.  

## Tecnologias  
- Java 17 + Spring Boot 3  
- Spring Security + JWT  
- PostgreSQL  

## Endpoints  
- `POST /auth/signup`  
- `POST /auth/login`  
- `GET /profile` (protegido)  
