# Домашнее задание по занятию "Оркестрация группой Docker контейнеров на примере Docker Compose." - `Фомичев Анатолий`


## Ссылка на домашнее задание - https://github.com/netology-code/virtd-homeworks/blob/shvirtd-1/05-virt-03-docker-intro/README.md


### Задача 1

docker.hub
https://hub.docker.com/repository/docker/kegp/custom-nginx/general
  
 
Скриншоты выполнения:

   
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_685.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_686.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_687.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_688.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_689.png).


### Задача 2

![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_690.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_691.png).


### Задача 3

Контейнер остановился, потому что его главный процесс (nginx) получил сигнал SIGINT (Ctrl+C) и завершил свою работу. Когда главный процесс контейнера останавливается, Docker автоматически переводит контейнер в статус Exited
  
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_692.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_693.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_694.png).


При запуске контейнера проброшен порт хоста 8080 на порт 80 контейнера (-p 127.0.0.1:8080:80). Это статическое правило, которое не меняется автоматически при изменении конфигурации внутри контейнера. Мы же внутри контейнера перенастроили Nginx слушать порт 81. Трафик с хоста приходит на порт 80 контейнера, но там никто не отвечает (nginx слушает 81-й порт). Внутри контейнера сервер доступен на порту 81, но этот порт не опубликован наружу.  
  
  
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_695.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_696.png).



  
### Задача 4

  
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_697.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_698.png).


  

### Задача 5
  
  
  
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_699.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_700.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_701.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_702.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_703.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_704.png).
![alt text](https://github.com/SLzDevOps/netology-virt-3/blob/main/screenshots/Screenshot_705.png).



  
  
