
 execution sous docker
 docker build -t example/vertx .
 docker run -d -t -i -p 8080:8080 example/vertx

 ${docker-machine ip}/8080