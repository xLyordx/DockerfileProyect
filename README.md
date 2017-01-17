# DockerfileProyect

## Como se crea la imagen??

## para correr el dockerfile
docker run --name "nombre del contenedor" -h "host del contenedor" -d -p mapeo de puertos separados por dos puntos (8081:8080) apache -p mapea el puerto de mongo (27017:27017) nombre de la imagen creada con el dockerfile.

## hay un error que mongo no se ejecuta, entonces para ejecutarlo
se ejecuta
docker exec nombredelcontenedor mongod y cerrar la terminal

pendiente actualizar db

