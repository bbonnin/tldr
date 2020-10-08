# docker build

> Construction d'une image à partir d'un Dockerfile.
> Plus d'informations: <https://docs.docker.com/engine/reference/commandline/build/>.

- Construire une image docker en utilisant le Dockerfile du répertoire courant:

`docker build .`

- Construire une image docker en spécifiant l'URL du Dockerfile:

`docker build {{github.com/creack/docker-firefox}}`

- Construie une image docker et la tagger:

`docker build --tag {{name:tag}} .`

- Construire une image sans utiliser le cache:

`docker build --no-cache --tag {{name:tag}} .`

- Construire une image docker en spécifiant le Dockerfile:

`docker build --file {{Dockerfile}} .`

- Construire une image en spécifiant des valeurs pour des variables d'environnement:

`docker build --build-arg {{HTTP_PROXY=http://10.20.30.2:1234}} --build-arg {{FTP_PROXY=http://40.50.60.5:4567}} .`
