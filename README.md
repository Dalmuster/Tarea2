# Tarea2
1- Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo

La descargué mediante el comando sudo docker pull alpine y comprobé que estaba en el repositorio mediante sudo docker images

2-Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre

Lo creo mediante el comando sudo docker run -d alpine y gracias a sudo docker ps -a se puede ver que creo el nombre aleatorio en este caso wizardly_cray.

3-Crea un contenedor con el nombre 'dam_alp1'. ¿Como puedes acceder a él?

Se crea con el comando sudo docker run --name=dam_alp1 alpine /bin/sh, se puede acceder a el con el comando docker exec -it dam_alp1 /bin/bash.

4-Comprueba que ip tiene y si puedes hacer un ping a google.com

Tiene la ip 172.17.0.2 y si puede hacer ping a google.

5-Crea un contenedor con el nombre 'dam_alp2'. ¿Puedes hacer ping entre los contenedores?

Se crea con el comando sudo docker run --name=dam_alp2 alpine /bin/sh, si se puede hacer ping entre los contenedores.

6-Sal del terminal, ¿que ocurrió con el contenedor?

Sigue en ejecución.

7-¿Cuanta memoria en el disco duro ocupaste?

Para los dos se utiliza un total de 0,02% de memoria.

8-¿Cuanta RAM ocupan los contenedores? ¿Hay algún comando docker para saber esto?.

Los contenedores ocupan entre los dos 1040KiB para saberlo existe el comando sudo docker stats
