# DS Post with MongoDB

Projeto didático ministrado pelo professor Dr. Nelio Alves no capítulo 7: Workshop NoSQL MongoDB referenete ao módulo Java Spring Reference.

Link de acesso: https://devsuperior.club

Este projeto tem como intuito construir uma API REST para manipulação de usuários e posts com conexão com banco de dados NoSQL utilizando 
Spring Boot e MongoDB. 

### Container Docker do MongoDB para desenvolvimento

```
docker run -d -p 27017:27017 -v /data/db --name mongo1 mongo:4.4.3-bionic
```

```
docker exec -it mongo1 bash
```
