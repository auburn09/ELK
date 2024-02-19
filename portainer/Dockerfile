FROM ubuntu:22.04
ENTRYPOINT echo "Hello my FEIRST Docker"


LABEL authors="semenov_av"
LABEL type="Тестовый докер файл для portainer"
RUN apt-get update
RUN apt-get install nginx -y
RUN apt-get clean && rm -rf /var/lib/apt/list/*
WORKDIR /var/www/html/
COPY files/index.html .
ENV OWNER = demo
ENV TYPE =  demo2
EXPOSE 80
EXPOSE 443/tcp
ENTRYPOINT ["NGNIX", "-g", "daemon off;" ]
//запуск NGNIx в контейнере

mkdir docker
    //создаем каталог docker


cd docker
    //переходим в него \
    ll
    // просмотр каталога по файлам

touch dockerfile
    // создаем файл

ll
    // просмотр каталога по файлам

vi dockerfile
    // редактируем

//вставляем содержимое докерфайла


docker build -t myimage:v01
    //скомпилирует dockerile в имадж с именем myimage:v01

docker image - посмотреть имаджи
docker tag djkfghkdfg984 (ID Image) mydocker:v01
    //Добавить имя и тэг v01 имаджу djkfghkdfg984 mydocker:v01

docker run --rm --name mydocker mydocker:v01
    //создаем контейнер с автоудалением при остановке с именем mydocker из образа mydocker:v01
docker run --rm --name mydocker myimage:v01
    //создаем контейнер с автоудалением с именем myimage:v01

docker run --it --rm --name mydocker myimage:v01 /bin/bash
    //cоздаем контейнер с автоудалением с именем myimage:v01 в интерактивном режиме (--it) без запуска команд

docker run -d --rm --name mydocker myimage:v01
    //cоздаем контейнер с автоудалением с именем myimage:v01 в дебаг режиме (-d)

docker ps
    //запущенные контейнеры

docker exec -it 6811a5fab4d0 /bin/bash
sudo docker run -it --entrypoint /bin/bash 6811a5fab4d0

sudo docker run -it --entrypoint /bin/bash kibana:8.12.1

/usr/share/kibana/bin/kibana-verification-code


    //войти в контейнер
    ps xs
        //просмотр процессов в контейнере
netstat -tulpen











