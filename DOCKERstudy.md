
# часть 1 - основные команды
## docker pull - скачать образ
## docker rm - удалить контейнер
## docker rmi - удалить образ
## docker run - запустить контейнер
## docker images - посмотреть образы
## docker ps -a
## docker run ubuntu sleep 5
## docker run -d ubuntu sleep 10
## docker start "название контейнера"
## docker run ubuntu:20.04 <- версия
## docker pause
## docker unpause
## docker run -d --rm ubuntu sleep 900 
## docker inspect 359a..
## docker stats
## docker run -d --rm --name MyNginx nginx
## docker logs e53...
## docker exec -it MyNginx /bin/bash
## docker system prune -a --volumes
# часть 2 - управление портами
## docker run -p 80:80 nginx
## docker run -p 8080:80 nginx
## netstat -tulpen
## docker run -d --name web -p 80:80 nginx
## sudo ss -ltnp | grep "80"
## sudo systemctl stop httpd
# sudo pkill httpd
