# Spring Boot WebFlux example: Building CRUD REST API

Spring Boot WebFlux Rest API example - CRUD application that uses Spring Data Reactive (R2DBC) to interact with embedded database. You'll know:
- Overview of Reactive Programming and handling Blocking and Non-blocking requests
- How to configure Spring Data Reactive, R2DBC to work with Database
- How to define Data Models and Repository interfaces
- Way to create Spring Rest Controller to process HTTP requests
- Way to use Spring Data R2DBC to interact with Database

Methods	  Urls	                          Actions <br/>
POST	    /api/tutorials	                create new Tutorial <br/>
GET	      /api/tutorials	                retrieve all Tutorials <br/>
GET	      /api/tutorials/:id	            retrieve a Tutorial by :id <br/>
PUT	      /api/tutorials/:id	            update a Tutorial by :id <br/>
DELETE	  /api/tutorials/:id	            delete a Tutorial by :id <br/>
DELETE	  /api/tutorials	                delete all Tutorials <br/>
GET	      /api/tutorials/published	      find all published Tutorials <br/>
GET	      /api/tutorials?title=[keyword]	find all Tutorials which title contains keyword
