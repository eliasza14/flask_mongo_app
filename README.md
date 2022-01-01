# Flask Mongo App
This repository holds a simple Flask App which communicates with MongoDB in the context of the course "Python & Cloud Computing".

The easiest way to test and run the entire application is by using
[docker](https://docs.docker.com/engine/install/) and
[docker-compose](https://docs.docker.com/compose/install/). Then you can
simply launch the following commands to start-up everything and build the
projects.

1. Build the docker images: `docker-compose build`
2. Start the services:`docker-compose up -d`
3. (Optional) Stop the services and destroy volumes:`docker-compose down -v`

The compilation of the backend usually takes most of the time so you can
check the logs to if everything is ready using the following command.
```
docker logs -f mf_build_backend
```
To check that everything is ready you can enter the following urls
on your browser.
```
Home Flash App Page
http://localhost:5000/ 
  
Database response 
http://localhost:5000/animals
```
