1- creo un repositorio en docker hub llamado alanerm87/ejercicio02
2- docker pull nicopaez/pingapp:3.0.0
3- docker image tag nicopaez/pingapp:3.0.0 alanerm87/ejercicio02:1.0.0
4- docker push alanerm87/ejercicio02:1.0.0
5- docker pull alanerm87/ejercicio02:1.0.0
6- docker run --name ejercicio02 -d alanerm87/ejercicio02:1.0.0
