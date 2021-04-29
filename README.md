Estou testando e entendendo esse código, porém, como ainda tem alguns conceitos que preciso entender, estou assistindo as aulas
de banco de dados para terminar este projeto, a medida que for avançando, atualizarei o repositório


# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois

## Stack utilizada

  * Java8
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor
  
  

### Slides de palestra: https://speakerdeck.com/kamilahsantos/live-coding-dio-api-de-herois-com-spring-webflux

### Palestra garavda: https://www.youtube.com/watch?v=1VllPZYn6RI&t=3257s







### Executar dynamo: 

 na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb
 
para listar as tabelas criadas:  aws dynamodb list-tables --endpoint-url http://localhost:8000


documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
