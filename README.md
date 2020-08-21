# Product-Order-Microservice
A simple spring cloud example using **Config-Server**, **Eureka** , **Ribbon**& **Zuul Gateway**

## How to run on local machine
- Download the source code
- Initialize git repository in the config-repo folder and do git commit
- Update the spring.cloud.config.server.git.uri in the config-server application properties
- Run the config-server application
- Run the eureka-server application
- Run the gateway application
- Run the product & order application
- Open http://localhost:8761 to see the eureka dashboard.
- Make sure there are four entries i.e. config-server, product-service, order-service, zuul-server.
- Hit http://localhost:8765/orders/order you will see the port for order controller and  product controller