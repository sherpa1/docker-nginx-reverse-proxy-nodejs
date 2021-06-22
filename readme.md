# Docker + Reverse Proxy Nginx + Node.js

Mise en place d'une API Rest avec Node.js derrière un Reverse Proxy Nginx en tant que service Docker.

## Test

### Service Whoami

`curl -i localhost:80`

### Service API

`curl -i localhost:3000`



## Test avec faux noms de domaine
Modifier le fichier `/etc/hosts` afin de tester en local la résolution des noms de domaine de test

- 127.0.0.1   api.test
- 127.0.0.1   whoami.test

`curl -i api.test`

`curl -i whoami.test`


## Crédits

Inspiré par l'article : https://www.grottedubarbu.fr/docker-nginx-reverse-proxy/

---

**Alexandre Leroux**

- _Mail_ : alex@sherpa.one
- _Github_ : sherpa1
- _Twitter_ : @_sherpa_
- _Discord_ : sherpa#3890

_Enseignant vacataire à l'Université de Lorraine_

- IUT Nancy-Charlemagne (LP Ciasie)

- Institut des Sciences du Digital, Management & Cognition (Masters Sciences Cognitives)
