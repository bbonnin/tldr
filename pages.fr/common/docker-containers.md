# docker container

> Gère les conteneurs Docker.
> Plus d'informations: <https://docs.docker.com/engine/reference/commandline/container/>.

- Liste les conteneurs Docker en cours d'exécution:

`docker container ls`

- Démarre un ou plusieurs conteneurs arrêtés:

`docker container start {{container1_name}} {{container2_name}}`

- Tue un conteneur en cours d'exécution:

`docker container kill {{container_name}}`

- Arrête un conteneur en cours d'exécution:

`docker container stop {{container_name}}`

- Met en pause tous les processus à l'intérieur d'un conteneur:

`docker container pause {{container_name}}`

- Affiche des informations détaillées sur un conteneur:

`docker container inspect {{container_name}}`

- Exporte le système de fichier d'un conteneur au format d'une archive tar:

`docker container export {{container_name}}`

- Crée une nouvelle image à partir des modifications d'un conteneur:

`docker container commit {{container_name}}`
