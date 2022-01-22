# Teampass docker-compose

$ mkdir -p ./volumes/{teampass,db}

$ docker-compose up -d

Контейнер пересобран, чтобы решить проблему расхождения времени.

Команда для резервного копирования db:

$ docker exec teampass php /var/www/html/backups/script.backup.php  -k <токен>

