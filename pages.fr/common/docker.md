# docker

> Gère les conteneurs et les images Docker.
> Plus d'informations: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Lister les conteneurs Docker en cours d'exécution:

`docker ps`

- Lister tous les conteneurs Docker (en cours d'exécution et arrêtés):

`docker ps -a`

- Démarrer un conteneur à partir d'une image, avec un nom personalisé:

`docker run --name {{container_name}} {{image}}`

- Démarrer ou arrêter un conteneur existant:

`docker {{start|stop}} {{container_name}}`

- Récupérer une image d'un registre Docker:

`docker pull {{image}}`

- Ouvrir un shell à l'intérieur d'un conteneur en cours d'exécution:

`docker exec -it {{container_name}} {{sh}}`

- Supprimer un conteneur arrêté:

`docker rm {{container_name}}`

- Récupérer et surveiller les logs d'un conteneur:

`docker logs -f {{container_name}}`
