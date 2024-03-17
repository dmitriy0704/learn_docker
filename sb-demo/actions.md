### Шаги для запуска приложения:  
___1. Сборка jar:___
```shell
mvn clean package
```
___2. Сборка образа:___
```shell
docker build -t springboot-docker-demo .
```
___3. Запуск контейнера на основе обаза:___
```shell
docker run -i -t -p 8080:8080 --name springboot-docker-demo springboot-docker
```