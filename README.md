# Spring Boot 3 JWT Security

Demostração da implementação de segurança usando Spring Boot 3.0 e JSON Web Tokens (JWT).

## Recursos

* Cadastro de usuário e login com autenticação JWT;

* Criptografia de senha usando BCrypt;

* Autorização baseada em função com Spring Security;

* Tratamento personalizado de negação de acesso;

## Tecnologias

* Spring Boot 3.0

* Spring Security

* JSON Web Tokens (JWT)

* BCrypt

* Maven

## Executando

Você precisará ter o seguinte instalado em sua máquina local:

* Docker

```sh
docker compose up -d
```

ou

* Java JDK 17+

* Maven 3+

* Postgres (Necessário configurar conexão)*

### Para criar e executar o projeto, siga estas etapas

Clone o repositório: git clone <https://github.com/natanaelsc/spring-boot-3-jwt-security.git>
Navegue até o diretório do projeto: cd spring-boot-security-jwt
Compile o projeto: mvn clean install
Execute o projeto: mvn spring-boot:run

→ O aplicativo estará disponível em <http://localhost:8080>.
