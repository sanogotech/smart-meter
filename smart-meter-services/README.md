## Build

docker-compose  build
docker-compose  up
=======


##  Lancer les microservices dans cet ordre :
- config-server
- discovery-server
- zuul-server
- zipkin-server-2.12.9-exec.jar
- spring-admin
- books
- clientui

## Depuis un navigateur Web, accéder aux URL suivantes :
localhost:2002 -->> Eureka : liste des instances des microservices
localhost:2000/books/books/2

