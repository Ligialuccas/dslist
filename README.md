# 🎮 DSList

DSList é uma aplicação web desenvolvida com Spring Boot que permite aos usuários visualizar e organizar uma lista de jogos.


## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

-   **Java**: Linguagem de programação principal.
-   **Spring Boot**: Framework Java para desenvolvimento rápido de aplicações web e microsserviços.
-   **JPA/Hibernate**: Para persistência de dados e interação com o banco de dados.
-   **Banco de Dados H2**: Um banco de dados embutido para desenvolvimento (a configuração para um banco de dados mais robusto como PostgreSQL pode estar presente ou ser facilmente adicionada).
-   **Maven**: Ferramenta de gerenciamento de dependências e build.
-   **Postman**: para testes de API
  
## 🔧 Endpoints da API

-   `GET /games`: Lista todos os jogos.
-   `GET /games/{id}`: Retorna um jogo específico pelo seu ID.
-   `GET /lists`: Lista todas as listas de jogos.
-   `GET /lists/{id}`: Retorna uma lista de jogos específica pelo seu ID.
-   `GET /lists/{listId}/games`: Lista os jogos dentro de uma lista específica.
-   `PUT /lists/{listId}/replacement`: Reordena os jogos dentro de uma lista.


