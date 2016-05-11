### Postgress DB

Built on top of https://hub.docker.com/_/postgres/

Run below command to pull and start postgress db
```
docker run --name postgress -p 5432:5432 -e POSTGRES_PASSWORD=tc -e POSTGRES_USER=tc -d ananthhh/postgress
```
