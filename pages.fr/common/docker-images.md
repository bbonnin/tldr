# docker images

> Gère les images Docker.
> Plus d'informations: <https://docs.docker.com/engine/reference/commandline/images/>.

- Lister toutes les images Docker:

`docker images`

- Lister toutes les images Docker en incluant les images intermédiaires:

`docker images -a`

- Lister les images Docker en affichant que les IDs numériques:

`docker images -q`

- Lister les images Docker non utilisées par des conteneurs:

`docker images --filter dangling=true`
