# Docker + Reverse Proxy Nginx + Node.js + MySQL

Mise en place d'une API Rest avec Node.js derrière un Reverse Proxy Nginx.

## Test

Service Whoami
`curl -i localhost:80`

Service API
`curl -i localhost:3000`



## Test avec faux noms de domaine
Modifier le fichier /etc/hosts

127.0.0.1   api.test
127.0.0.1   whoami.test

`curl -i api.test`

`curl -i whoami.test`


## Crédits

Inspiré par l'article : https://www.grottedubarbu.fr/docker-nginx-reverse-proxy/
