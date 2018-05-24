# Requirements
- docker ce
- docker-compose
# Use
```sh
$ docker-compose up -d && docker logs react-template-1 -f
```
# Development
Docker run as root, the directories only modified for root. If you want to modify run this on the directory /react-template-docker:
```
$ sudo chmod -R 777 .
```



