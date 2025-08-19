    ```
    ### Para correr el Docker

    cd .\docker

    ### Para correr el contenedor
    docker-compose up -d

    ### Para comprobar el estado (ya estando corriendo el contenedor)
    docker ps

    ### Para acceder a MySQL
    docker exec -it mysql_bbdd_I3G2 mysql -u root -p

    ## Luego ingresar la contraseña configrada (MYSQL_ROOT_PASSWORD)

    ### Para salir de MySQL
    exit;

    ### Para detener el contenedor
    docker-compose down

    ```