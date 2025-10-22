# API Rest - Gerenciador Tarefas

Esse projeto foi desenvolvido com Java e Spring Boot, que permite o gerenciamento de tarefas

---

## Funcionalidades

  - CRUD de tarefas
  - CRUD de categoria de tarefas

---

## Destaques

  - Banco de dados local
  - Entidades modeladas


---

## Tecnologias

- Java 17
- Spring Boot 3
- Spring Data JPA
- H2 Database

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/api-produtos-categorias.git
   cd api-produtos-categorias
   
   
## Execute o projeto com Maven:
  - ```bash
    ./mvnw spring-boot:run

## Endpoints da API

| Método | URL                        | Descrição                        |
|--------|----------------------------|----------------------------------|
| GET    | /listarCategoria           | Listar categorias                |
| PUT    | /salvarCategoria/{id}      | Salvar categoria                 |
| GET    | /editarCategoria/{id}      | Editar categoria                 |
| DELETE | /excluirCategoria/{id}     | Excluir categoria                |
| GET    | /listarUsuarios            | Listar Usuários                  |
| GET    | /editarUsuario/{id}        | Atualizar produto                |
| PUT    | /salvarUsuario/{id}        | Salvar produto                   |
| DELETE | /excluirUsuario/{id}       | Excluir usuário                  |
| GET    | /listarTarefa              | Listar Tarefas                   |
| PUT    | /salvarTarefa/{id}         | Salvar Tarefa                    |
| GET    | /editarTarefa/{id}         | Editar Tarefa                    |
| DELETE | /excluirTarefa/{id}        | Excluir Tarefa                   |
