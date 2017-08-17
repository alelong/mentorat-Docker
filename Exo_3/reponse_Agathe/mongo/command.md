Exercice 1:
$docker run --name container-mongo -d mongo

Exerice 2:
$docker build -t mymongoimage:0.1
$docker run --name container-mongo -p 27017:27017 -d mymongoimage:0.1

Exercice 3:
$docker-compose up -d
