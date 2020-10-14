# Flask Template 

Run flask-app on docker from the root directory:
* For the first time or to recreate the containers (performs every step on the Dockerfile):
    ~~~~
    docker-compose up --build
    ~~~~
* Any other time:
    ~~~~
    docker-compose up
    ~~~~
The previous command will create two containers:
* `flask-app`: is a flask template built on ubuntu 16.04 image.


`flask-app` allows hot reloading from the local repository folder.

### Docker Compose:
https://docs.docker.com/compose/

### Docker Cheat Sheet:
http://dockerlabs.collabnix.com/docker/cheatsheet/