# spring-cloud-netflix
All components of netflix microservices enviroment

First, create an entry on /etc/hosts 
127.0.0.1	config-server

Import the project config-server and start. The config server will start in 8001 port.

Import the project service-discovery and start. The service discovery will start in 8761 port.
You can call http://localhost:8761 in browser to see eureka console


Import the project service-discovery and start. The api gateway will start in 9090 port.
You can call http://localhost:8761 in browser to see eureka console, now there are 2 services in Eureka, service-discovery and api-gateway

