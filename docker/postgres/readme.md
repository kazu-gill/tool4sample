# docker-compose for learning
## It also creates a valid VOLUME 

```shell
$ docker volume create storage  
$ docker volume create pgadmin  
```

## docker-composer 
Download or clone and run the command.

```docker 
docker-compose up -d
```
## connect
url localhost:8000 pgmyadmin.
In the compose.yml file
- PGADMIN_DEFAULT_EMAIL
- PGADMIN_DEFAULT_PASSWORD　　
is the initial login information for pgadmin4.
It can be rewritten and used as desired.

