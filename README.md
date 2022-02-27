# Paint World Mobile Application
An interactive playful application for children - software engineering course @ La Sapienza


## Project Structure





>
### Docker image for the mysql server with complete database.
>
> https://hub.docker.com/repository/docker/1972811/paint-world-swe

#### Dockerfile present in the parent directory of the repo.

>
How to run the docker container?
```
docker run --name some-mysql-name -p 3306:3306 -e MYSQL_ROOT_PASSWORD=password -d mysql_image_name:tag
```
[further read/reference](https://github.com/bazzani/mysql-5.5-docker)
