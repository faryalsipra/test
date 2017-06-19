# MySQL tests

## MySQL Server
Running Mysql server in a docker container

```
$ mkdir mysql
$ cd mysql
$ docker run -p 3306:3306 --name mysql -v `pwd`:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=root -d mysql:5.7.18
```
