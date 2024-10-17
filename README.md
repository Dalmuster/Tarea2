# Tarea2
1- Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo

La descargué mediante el comando 

--sudo docker pull alpine 

Y comprobé que estaba en el repositorio mediante 

--sudo docker images

2-Crea un contenedor sin ponerle nombre. ¿está arrancado? Obtén el nombre

Lo creo mediante el comando 

--sudo docker run -d alpine 

Y gracias a 

--sudo docker ps -a 

Se puede ver que creo el nombre aleatorio en este caso wizardly_cray.


