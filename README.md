
version: '3'
services:
 microservice1:
  image: microservice1
  container_name: microservice_1
  networks:
    - micro-network
 microservice2:
  image: microservice2
  container_name: microservice_2
  networks:
    - micro-network
networks: 
  micro-network:
