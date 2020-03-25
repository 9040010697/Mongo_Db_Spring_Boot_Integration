This Application is saving data in to mongo data extrenal base , Which is a no sql database , 
to use first we need to install mongo db  and after that we need to create database and collection inside that.

same database name and collection name we need to mentioned in model class @Document(...)

by default mongo db port is :27017

Example: 
spring.data.mongodb.database=product
spring.data.mongodb.port=27017
spring.data.mongodb.host=localhost
