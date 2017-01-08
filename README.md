docker build -t=babymamagotback .

docker run -d --link MariaDB:mariadb.docker --name babymamagotback babymamagotback
