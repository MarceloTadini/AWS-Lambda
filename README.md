# :books: Funções AWS LAMBDA para API REST

## :mag_right: Conceitos Utilizados
* Rotas Http
* Amazon Web Services

##  :video_game: Tecnologias Utilizadas 
* JavaScript;
* Amazon Web Services:
  1. DynamoDb;
  2. API Gateway
  3. Lambda
* Client URL (CURL)

## :rocket: Como executar 
* Para adicionar um dado:
````curl -X "PUT" -H "Content-Type: application/json" -d "{\"id\": \"123\", \"price\": 12345, \"name\": \"myitem\"}" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items````

* Para adicionar outro dado:
````curl -X "PUT" -H "Content-Type: application/json" -d "{\"id\": \"456\", \"price\": 789, \"name\": \"myitem2s\"}" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items````

* Para listar os dados:
````curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items````

* Para listar um dado com ID específico:
````curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items/789````

* Para deletar um dado com ID específico:
````curl -X "DELETE" https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items/789````

* Para listar os dados:
````curl https://pn2qh7tb2j.execute-api.us-east-1.amazonaws.com/items````
