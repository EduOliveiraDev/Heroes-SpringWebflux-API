# Como rodar o projeto
1. Fazer o clone do projeto
2. Importar o projeto no intellij
3. Rodar o comando do docker para criar o container do dynamodb-local
    ```shell script
    docker run -p 8000:8000 -d --name dynamoDbLocal amazon/dynamodb-local
    ```
4. Executar classe ```HeroesTable``` no Intellij para criar a tabela no dynamodb
5. Executar classe ```HeroesData``` no Intellij para inserir os registros
6. Executar classe ```HeroesApiApplication``` no Intellij para iniciar a aplicação web
7. Acessar url com a api swagger http://localhost:8080/swagger-ui-heroes-reactive-api.html


# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois

## Stack utilizada

  * Java17
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor
  
  

### Slides de palestra: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux

### Palestra garavda: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s



documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
