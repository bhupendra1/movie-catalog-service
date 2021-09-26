# movie-catalog-service
Movie Catalog Microservice that uses service discovery pattern to discover and communicate with other microservices (movie-info-service &amp; ratings-data-service)

This service also utilizes Netflix's Hystrix library to implement circuit breaker pattern and become a fault tolerant microservice.

This microservice calls movie-info-service and ratings-data-service to display information about all the movies that the user have watched and given ratings on (along with what ratings they have given to a specific movie)
