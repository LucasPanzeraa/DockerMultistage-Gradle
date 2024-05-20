# DockerMultistage-Gradle
Carone Thiago - Panzera Lucas

Para generar y correr una imagen docker se deben de seguir los siguientes pasos:

1) docker build -t nombre_deseado .
   
Se crea un container en base a los contenidos especificados en el Dockerfile.


2) docker run -p puerto_exterior:puerto_interior nombre_de_la_imagen
   
Se corre el docker en el puerto interor indicado a partir de los datos del puerto exterior.
