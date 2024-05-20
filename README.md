

# Aplicativo Web Spring Boot CRUD

## OBS: Para facilitar o uso, abrir o projeto no Intellij!

## Visão Geral do Projeto

Este aplicativo web segue o design MVC e foi desenvolvido usando Java com Spring Boot. Ele apresenta um sistema CRUD completo, armazenando dados em um banco de dados MySQL. A interface do usuário foi criada com HTML, CSS, Bootstrap e Thymeleaf, enquanto o JavaScript foi empregado para validar regras de negócio específicas. O aplicativo também inclui funcionalidades adicionais como autenticação de usuário, criptografia de dados sensíveis, e mais.

## Stack Tecnológica

- Java 17
- Spring Boot 2.6
- JPA/Hibernate
- Maven
- HTML/CSS/JavaScript
- Bootstrap
- MySQL

## Demonstração em Ação

[!Demonstração do Aplicativo](https://user-images.githubusercontent.com/89096854/170026187-57aa04f4-189b-4c00-8cc8-16a1227a5eb7.gif)

### Tela de Registro
![Tela de Registro] (https://user-images.githubusercontent.com/89096854/170031976-645e9bd8-eaca-4a84-805c-588100e1a770.PNG)


### Visualização dos Estudantes
!Visualização dos Estudantes(https://user-images.githubusercontent.com/89096854/170031981-68cf5454-a727-467c-82e6-1ba2f53c2900.PNG)

## Estrutura do Banco de Dados
!Banco (https://user-images.githubusercontent.com/89096854/170030916-5c05c8c3-71d7-432e-aa6c-02b0ccf30409.PNG)


## Guia de Instalação

Gerenciado pelo Maven, o projeto pode ser facilmente importado para qualquer IDE compatível.

## Configuração do Banco de Dados
Para configurar o banco de dados MySQL, crie uma nova base de dados e ajuste as configurações do projeto. Modifique os seguintes parâmetros no arquivo `application.properties` em `src/main/resources`:

```properties
spring.datasource.url = jdbc:mysql://localhost:3306/seu_banco_de_dados?useTimezone=true&serverTimezone=UTC
spring.datasource.username = seu_usuario
spring.datasource.password = sua_senha
```

## Como Executar
Inicie o aplicativo pela IDE, abra o navegador de sua escolha e acesse: http://localhost:8080

