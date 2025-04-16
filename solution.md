#Решение

[Задание 1] https://hub.docker.com/repository/docker/shurovej/custom-nginx/general

[Задание 2] https://github.com/Shurovej/Docker-Compose/blob/main/task2.png

[Задание 3] https://github.com/Shurovej/Docker-Compose/blob/main/task3.1.png

      https://github.com/Shurovej/Docker-Compose/blob/main/task3.2.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task3.3.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task3.4.png
                  
      Кратко объясните суть возникшей проблемы - мы сломали мэпинг (проброс портов с хостовой машины докер в докер контейнер) проброс настроен на 80й порт, а nginx слушает 81й

[Задание 4] https://github.com/Shurovej/Docker-Compose/blob/main/task4.png

[Задание 5] https://github.com/Shurovej/Docker-Compose/blob/main/task5.1.png

      Какой из файлов был запущен и почему? - Будет запущен файл docker-compose.yaml, потому что:
Docker Compose по умолчанию ищет файлы с именами compose.yaml или docker-compose.yaml (в этом порядке)
Но команда docker compose (без дефиса) по умолчанию использует именно docker-compose.yaml

      https://github.com/Shurovej/Docker-Compose/blob/main/task5.2.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task5.3.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task5.4.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task5.5.png
      
      https://github.com/Shurovej/Docker-Compose/blob/main/task5.6.png
