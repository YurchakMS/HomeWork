---
### Задание 1
Создать свой контейнер nginx на базе образа Alpine.
- Для создания используем Dockerfile 
- запускаем сборку 'docker build -t myurchak/nginx ."
- смотрим ID получившигося контейнера

'''
$ sudo docker images
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
myrchak/nginx       0.31                818b6ed08805        About an hour ago   24MB
myurchak/nginx      0.31                818b6ed08805        About an hour ago   24MB
nginx               alpine              a624d888d69f        2 weeks ago         21.5MB
'''

- запускаем собранный контейнет 'docker run -d -p 8080:80  818b6ed08805'
