Exerice 1:
$docker run --name container-node -p 8000:8000 -d -v `pwd`:/js node node js/server.js

Exercice 2:
$docker build -t mynodeimage:0.1 .
$docker run --name container-node -p 8000:8000 -d mynodeimage:0.1

Exercice 3:
$docker tag agathe/mynodeimage:0.1 alelong/mentoratdocker:node
$docker-compose bundle --push-images
