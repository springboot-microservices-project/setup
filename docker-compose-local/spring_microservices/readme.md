### Run docker compose
`docker-compose up -d`


### Select all image success to download
`docker image ls "denitiawan/springboot-microservices-*"`


### Stop docker compose`
`docker-compose stop`


### Remove docker compose
`docker-compose rm`



### Removes all volume from this project
`docker volume prune`


### Remove all image from repository denitiawan/springboot....
* `docker image rm  denitiawan/springboot-microservices-discovery-service:latest`
* `docker image rm  denitiawan/springboot-microservices-gateway-service:latest`
* `docker image rm denitiawan/springboot-microservices-auth-service:latest`
* `docker image rm  denitiawan/springboot-microservices-master-service:latest`
* `docker image rm  denitiawan/springboot-microservices-inventory-service:latest`
* `docker image rm denitiawan/springboot-microservices-trans-service:latest`
* `docker image rm  denitiawan/springboot-microservices-schmaster-service:latest`
* `docker image rm  denitiawan/springboot-microservices-schtransaction-service:latest`
* `docker image rm  denitiawan/springboot-microservices-report-service:latest`
* `docker image rm  denitiawan/springboot-microservices-email-service:latest`
* `docker image rm  denitiawan/springboot-microservices-email-web:latest`
