# capital-numbers
#Manish Rai

Assignment for capital numbers

This repository contains following projects -

	1. Match Microservice
	
	2. Service Registry (using Eureka)
	
	3. API Gateway
	
Open API being used for documentation
    
Service names are being resolved using Service Registry.

Added Postman call for following services -

	1. Match Microservice
	
Used postgresSql, NamedParameterJdbcTemplate and Spring Transactions..

Run projects in following orders to consume the api ->

1. service-registry

2. api-gateway

3. match-seervice

api exposed through api-gateway.. api-gateway is single point for entry that internally use service-registry to resolve the actual service

API testing done via Postman and added the POSTMAN calling details in the below file, same can be imported in postman and can be tested after running the api -
Matches.postman_calls
