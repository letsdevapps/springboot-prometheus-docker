# no diretorio raiz do projeto

	mvn clean package
	
	docker build -t springboot-prometheus .
	
	docker run -p 8080:8080 -p 8081:8081 springboot-prometheus
	
## Endpoints API

Aplicação

    localhost:8080

Spring Actuator

    localhost:8081
