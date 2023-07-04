# Online food ordering System

<h2>Services</h2>

<h4>1. Search Service:</h4>

<p>Create Restaurant: Add restaurant</p>

<p>Search Restaurant: Search restaurants.</p>

<h4>2. Order Service: </h4>
<p>Place an order: Create an order at the restaurant.</p>

<p>Cancel order: Cancel your order at the restaurant.</p>

<p>Fetch orders: Get your order details.</p>

<p>Calculate the amount: Based on the number of items ordered per order.</p>

<h4>3. Aggregate Service</h4>
<p>Fetch Order By City</p>

<p>Calculate Orders Amount By City</p>

<h4>4. API Gateway</h4>
<p>Use the express-gateway npm package.</p>
  Express Gateway is an open-source API gateway that is commonly used in microservices and API-driven architectures.
  Express Gateway acts as a centralized entry point for all incoming API requests, allowing you to control and manage access to your APIs. It provides functionalities like authentication, authorization, rate limiting, and request/response transformations.

<h4>5. RabbitMQ Service</h4>



Monolithic vs Microservices architecture
----------------------------------------

Monolithic - 
1) All the services will be tightly coupled.
2) One service data may be dependent on other service data so if there will be changes in one service then the other service will also be changed.
3) In Monolithic, all the functionalities of a project exist in a single codebase.


Disadvantages of Monolithic applications: 
1) It becomes too large with time and hence, difficult to manage.
2) We need to redeploy the whole application, even for a small change.
3) As the size of the application increases, its start-up and deployment time also increases.


Microservices -
1) All the services will be loosely coupled.
2) All services will be independent.
3) But services can communicate with other services using the service registry.
4) If there’s any update in one of the microservices, then we need to redeploy only that microservice.


Why do we use API Gateway with Microservices - 
1) In microservices, there will be many services and many addresses.

Benefits of using API Gateway-
1) API gateway helps to provide additional security to your microservices.
2) We can do Authentication/Authorization.
3) Retry Policy.


DOCKER -

The command for creating docker Image-
docker build -t image_name.

The command for running the container-
docker container run --name web -p 3000:3000

The command for running the docker-compose.yml file-
docker-compose pull
