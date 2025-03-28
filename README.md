## **Spring Boot + Hibernate + MySQL CRUD API**

### **Descrição**
Este projeto é uma API REST desenvolvida com **Spring Boot**, **Hibernate** e **MySQL**, que implementa operações CRUD (Create, Read, Update, Delete) para gerenciar dados de usuários. Ele é ideal para aprender os fundamentos de persistência de dados usando JPA com Hibernate em um ambiente Spring Boot.

---

### **Tecnologias Utilizadas**
- **Spring Boot**: Framework para simplificar o desenvolvimento de aplicativos Java.
- **Spring Data JPA**: Integração com Hibernate para mapeamento objeto-relacional.
- **Hibernate**: Implementação de JPA para persistência de dados.
- **MySQL**: Banco de dados relacional utilizado no projeto.
- **Postman**: Ferramenta para testar os endpoints da API.

---

### **Endpoints Disponíveis**
1. **POST /usuarios**: Cria um novo usuário.
2. **GET /usuarios**: Retorna todos os usuários.
3. **GET /usuarios/{id}**: Retorna os detalhes de um usuário específico.
4. **PUT /usuarios/{id}**: Atualiza os dados de um usuário.
5. **DELETE /usuarios/{id}**: Exclui um usuário.

---

### **Configuração do Banco de Dados**
Certifique-se de que o MySQL está em execução e crie um banco de dados chamado `spring_hibernate`. Atualize o arquivo `application.properties` com suas credenciais:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/spring_hibernate?useSSL=false&serverTimezone=UTC
spring.datasource.username=SEU_USUARIO
spring.datasource.password=SUA_SENHA
```

---

### **Como Executar o Projeto**
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   ```  
2. Importe o projeto para sua IDE (Eclipse/IntelliJ).
3. Certifique-se de que o MySQL está configurado e rodando.
4. Execute a aplicação através da classe principal (`DemoApplication.java`).
5. Use o Postman ou outra ferramenta para testar os endpoints.

---

### **Contribuições**
Sinta-se à vontade para abrir issues e enviar pull requests com melhorias ou correções.

---
