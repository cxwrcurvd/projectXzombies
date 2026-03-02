## Welcome to Docker

Репозиторий welcome-to-doker для обучения базе докера и его функций


> Перед созданием проекта убедитесь, что порт 8088 не занят другим приложением!



Открытый порт 8088

<a href="https://imgbb.com/"><img src="https://i.ibb.co/fdvTtHDQ/photo-2026-03-02-13-44-19.jpg" alt="photo 2026 03 02 13 44 19" border="0"></a>



Загрузка образа и запуск контейнера
docker run -d -p 8088:80 --name welcome-to-docker docker/welcome-to-docker




<a href="https://ibb.co/Psff4Q0f"><img src="https://i.ibb.co/hxttHfwt/photo-2026-03-02-13-56-34.jpg" alt="photo-2026-03-02-13-56-34" border="0"></a>

[Открыть http://localhost:8088 в браузере](http://localhost:8088)

Скрин контейнера в браузере
<a href="https://ibb.co/NQNQbBr"><img src="https://i.ibb.co/49S93r2/photo-2026-03-02-14-00-21.jpg" alt="photo-2026-03-02-14-00-21" border="0"></a>



Зайти в контейнер
docker exec -it welcome-to-docker /bin/sh




Выполнение разных команд:

Инфа об ОС + монитор ресурсов
uname -a

top

<a href="https://ibb.co/5gp4fTW8"><img src="https://i.ibb.co/Vcn9PVWS/photo-2026-03-02-14-01-08.jpg" alt="photo-2026-03-02-14-01-08" border="0"></a>



Обновление программ
apk update && apk upgrade

<a href="https://ibb.co/bM3h6XbH"><img src="https://i.ibb.co/RkSngcjh/photo-2026-03-02-14-01-55.jpg" alt="photo-2026-03-02-14-01-55" border="0"></a>



Установка fastfetch и запуск fastfetch
apk add fastfetch

fastfetch

<a href="https://ibb.co/pv44WQvF"><img src="https://i.ibb.co/7JrrgQJm/photo-2026-03-02-14-02-45.jpg" alt="photo-2026-03-02-14-02-45" border="0"></a>



Выйти из образа обратно в основную систему
exit



Все скриншоты в папке docker/img