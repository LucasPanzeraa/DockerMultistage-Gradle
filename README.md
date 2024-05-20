# DockerMultistage-Gradle
Carone Thiago - Panzera Lucas

Para generar y correr una imagen docker se deben de seguir los siguientes pasos:

1) docker pull
   Se debe hacer el pull de la imagen que se desea usar desde la pagina de docker en nuestro caso.
  (docker pull gradle:jdk8-jammy y docker pull eclipse-temurin)

2) docker build -t nombre_deseado .
   
Se crea un container en base a los contenidos especificados en el Dockerfile.

3) docker run -p puerto_exterior:puerto_interior nombre_de_la_imagen
   
Se corre el docker en el puerto interor indicado a partir de los datos del puerto exterior.
