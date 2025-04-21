## Start the docker file

```sh
$ docker compose build
```
### Then migrate the database

```sh
$ docker compose run app npx prisma migrate dev --name init
```
### Starting up the docker file

```sh
$ docker compose up
```
