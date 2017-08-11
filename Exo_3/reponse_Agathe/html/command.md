Exercice 1:
$docker run --name container-nginx -p 80:80 -d -v `pwd`:/usr/share/nginx/html nginx

Exercice 2:
$docker build -t mynginximage:0.1 .
$docker run --name container-nginx -p 80:80 -d mynginximage:0.1
