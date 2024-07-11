
# API Gateway

## Spring Cloud Gateway 

### Ferramentas para executar
- Java 17
- Maven

API gateway é utilizado para centralizar e balancear requisições de instâncias em microsserviços registrados no 
Eureka Service Discovery. Quando utilizamos a porta do gateway podemos acessar os microsserviços registrados através
do nome. Exemplo:

    http://localhost:8082/application-ms/application

O gateway é utilizado também para colocar filtros para customizar o acesso a rotas.

_Essa aplicação foi desenvolvida para fins de estudo de load balancer, gateway e discovery service._