Projeto MVC - Sistema de Tarefas
Aplicação web desenvolvida em Java utilizando Spring Boot, seguindo o padrão MVC. O objetivo do projeto é demonstrar habilidades de desenvolvimento backend, integração com banco de dados, e aplicação de boas práticas no desenvolvimento de CRUD.

Sobre o projeto
Este sistema permite cadastrar, listar, pesquisar, visualizar detalhes e excluir tarefas. O projeto utiliza arquitetura MVC, camadas de serviço e repositório, além de templates HTML para renderização das páginas.

Ideal para portfólio acadêmico ou como base para sistemas de cadastro simples em Java.

Funcionalidades
Cadastro de tarefas

Listagem de tarefas

Pesquisa de tarefas

Visualização de detalhes da tarefa

Exclusão de tarefas

Templates HTML responsivos

Tecnologias Utilizadas
Java 17+

Spring Boot

Spring MVC

Spring Data JPA

Maven

Thymeleaf

Banco de dados relacional (configurável)

HTML5

Estrutura do Projeto
src/
└── main/
├── java/
│ └── br/
│ └── com/
│ └── fiap/
│ └── mvc/
│ ├── MvcApplication.java
│ ├── controller/
│ │ └── TarefaController.java
│ ├── model/
│ │ └── Tarefa.java
│ ├── Repository/
│ │ └── TarefaRepository.java
│ └── Service/
│ └── TarefaService.java
├── resources/
│ ├── application.properties
│ └── templates/
│ ├── tarefa-form.html
│ ├── tarefa-list.html
│ ├── tarefa-detalhes.html
│ ├── pesquisa-tarefa.html
│ └── Layout/
│ └── Base.html
└── joker.sql

controller/: controladores das rotas

model/: entidade de domínio Tarefa

Repository/: repositório JPA

Service/: camada de negócio

templates/: páginas HTML para interação com usuário

Como rodar o projeto localmente
Clone o repositório
git clone https://github.com/seuusuario/mvc-main.git
cd mvc-main

Configure o banco de dados
Edite o arquivo application.properties conforme suas configurações de banco (veja também o script joker.sql para criar a estrutura).

Compile o projeto
./mvnw clean install

Inicie a aplicação
./mvnw spring-boot:run

Acesse pelo navegador em http://localhost:8080

Autor
Vinicius Becker
Projeto desenvolvido para fins acadêmicos.
