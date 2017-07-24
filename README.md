![alt text](http://www.3pillarglobal.com/wp-content/uploads/2015/10/docker_logo_180x110.jpg "Docker")
# oracle-java8-ant
A container that adds Apache Ant on top of container sunithar/oracle-java8 (Oracle Express 11g R2 on Ubuntu 16.04 LTS with Java8).

### Build
```sh
docker build -t oracle-java8-ant .
```

### Run
```sh
docker run -it --rm oracle-java8-ant 
```
Run with ports 22 and 1521 mapped and opened
```sh
docker run -it --rm -d -p 49160:22 -p 49161:1521 oracle-java8-ant 
```

### Usage
This container can be used by anyone who needs Ubuntu, Oracle, Java8 and Ant as a base image







