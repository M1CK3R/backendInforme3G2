### Para correr el Docker

```bash

cd .\docker

```

### Para correr el contenedor

```bash

docker-compose up -d

```

### Para comprobar el estado (ya estando corriendo el contenedor)

```bash

docker ps

```


### Para acceder a MySQL

```bash

docker exec -it mysql_bbdd_I3G2 mysql -u root -p

```

#### Luego solo ingresar la contraseña configurada en docker-compose.yml (MYSQL_ROOT_PASSWORD)


### Para salir de MySQL

```bash

exit;

```


### Para detener el contenedor

```bash

docker-compose down

```