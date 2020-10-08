# docker logs

> Affiche les logs d'un conteneur.
> Plus d'informations: <https://docs.docker.com/engine/reference/commandline/logs>.

- Affiche les logs d'un conteneur:

`docker logs {{container_name}}`

- Affiche et surveille les logs d'un conteneur:

`docker logs -f {{container_name}}`

- Affiche les 5 dernières lignes:

`docker logs {{container_name}} --tail {{5}}`

- Affiche les logs en ajoutant un horodatage:

`docker logs -t {{container_name}}`

- Affiche les logs à partir d'un certain moment de l'exécution du conteneur (par exemple: 23m, 10s, 2013-01-02T13:23:37):

`docker logs {{container_name}} --until {{time}}`
