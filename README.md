# SpringBoot_API - Controle de Projetos

Este é um sistema simples de controle de projetos desenvolvido com Spring Boot, seguindo a arquitetura RESTful. Ele permite o cadastro, atualização, listagem e exclusão de projetos, sendo ideal como base para sistemas de gestão ou aprendizado de APIs Java.

## Tecnologias utilizadas

- Java 17  
- Spring Boot  
- Spring Data JPA  
- H2 Database  
- Maven  
- Lombok  

## Funcionalidades

- Listar projetos  
- Criar novo projeto  
- Atualizar projeto existente  
- Deletar projeto  

## Estrutura do projeto

src/ main/ java/ com/example/controleprojetos/ controller/ model/ repository/ service/ resources/ application.properties data.sql

## Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/Gustaa7K/SpringBoot_API.git
Importe o projeto no IntelliJ IDEA ou VS Code com suporte Java.

Execute a classe principal ControleProjetosApplication.java.

Acesse: http://localhost:8081

## Endpoints disponíveis

Metodo	Endpoint	Descricao
GET	/projetos	Lista todos os projetos
POST	/projetos	Cria um novo projeto
PUT	/projetos/{id}	Atualiza um projeto existente
DELETE	/projetos/{id}	Deleta um projeto

