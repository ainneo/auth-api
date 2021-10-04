# FAKE DOCKER BACKEND TO HOOK UP TO FRONTEND

HOOK UP TO THE FRONTEND:  https://www.youtube.com/watch?v=OUP-urBy1k4

# Usage

Make sure to install docker first https://www.docker.com/products/docker-desktop. After you installed docker run these commands

```
docker-compose up
```
Then after the images are pulled and are running open a new terminal tab and run
```
docker exec backend /bin/sh start.sh
```
The API is ready to be consumed on `http://localhost:8000`

# Updates & Issues
If you run into errors connecting to the faux backend, simply remove the MYSQL_USER from the docker ymal file. https://stackoverflow.com/questions/66831863/mysql-docker-container-keeps-restarting
