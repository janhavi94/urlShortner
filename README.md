# urlShortner

This is an API for Url shortener service like tiny url.

Url shortener is service that converts long urls into short urls. When user opens short url, it will be automatically redirected to original (long) url. It will also be shown all existing short URLs and the number of times it was used.

How to use
With Docker and docker-compose:
$ git clone https://github.com/AnteMarin/UrlShortener-API.git
$ cd UrlShortener-API 
$ docker-compose up 
- Open localhost:8080/swagger-ui.html to see endpoints. 
Without Docker:
$ git clone https://github.com/AnteMarin/UrlShortener-API.git
- Make sure you have access to local or any MySQL server.
- Open project in your favorite editor and change application.properties file to point to your MySQL database
- Build Spring project 
- Open localhost:8080/swagger-ui.html to see endpoints.

