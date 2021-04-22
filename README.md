:spiral_calendar: Atualizado em 10 de abril de 2021 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

# Projeto Digital Innovation One Java

# Desenvolvendo um sistema de gerencimanto de pessoas em API REST com Spring Boot - Java
- Este projeto foi proposto pela Digital Innovation One - Link do código original:https://github.com/rpeleias/personapi_digital_innovation_one
- Professor: Rodrigo Peleias
- Aulas: https://web.digitalinnovation.one/project/desenvolvendo-um-sistema-de-gerenciamento-de-pessoas-em-api-rest-com-spring-boot/learning/59e5edaa-470d-44a3-8519-c082d765c71d?back=/track/java-developer&bootcamp_id=73d4f45e-c71f-419d-b8f7-8c00a7a6af14

# Descrição
Aprenda a construir do zero uma API REST com Spring Boot para cadastro e gerenciamento de pessoas de uma organização, até o deploy na nuvem (Heroku). Pratique e veja os principais conceitos do modelo ARQUITETURAL REST envolvidos durante o desenvolvimento do projeto.

# Ajustes realizados para executar o projeto
- Foi necessário recompilar o projeto
- Rodei o npm install para carregar todas as dependências  
- Otimizei os imports

# Detalhes da aula

## Para executar o projeto no terminal, digite o seguinte comando:
```shell script
mvn spring-boot:run 
```
## Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:
```
http://localhost:8080/api/v1/people
```
## Verbos HTTP para executar no Postman
- POST - localhost:8080/api/v1/people
- GET - localhost:8080/api/v1/people      
- GET - localhost:8080/api/v1/people/{id}
- PUT - localhost:8080/api/v1/people/{id}
- DELETE - localhost:8080/api/v1/people/{id}