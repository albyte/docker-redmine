# docker-redmine 

# start
```
$ docker-compose up -d
$ docker-compose ps
           Name                         Command               State           Ports
--------------------------------------------------------------------------------------------
dockerredmine_redmine-db_1   docker-entrypoint.sh mysql ...   Up      3306/tcp
dockerredmine_redmine_1      /docker-entrypoint.sh rail ...   Up      0.0.0.0:8888->3000/tcp
```

## Redmine login
```
http://localhost:8888

ID: admin
PW: admin
```
