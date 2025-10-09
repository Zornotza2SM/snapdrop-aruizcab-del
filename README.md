# Despliega tu segunda aplicación con Docker (Snapdrop)

### 1. Ejercicio: Despliega el proyecto de docker compose y responde a las siguientes preguntas.


1. Snapdrop se trata de una aplicación para transferir archivos entre equipos a través de la red, averigua tu ip y trata de transferir archivos con algún compañero de clase, ambos teneis que conectaros al mismo servidor. Muestra una captura de la aplicación Snapdrop en el momento de recibir un archivo.

![alt text](image.png)

Por ejemplo, la dirección de este equipo es:
`INF200615-8GELA.zornotzalh.eus`

2. ¿Que puertos expone esta aplicacion? ¿Sabrías decirme para que protocolos e usan estos puertos?
Esta aplicación expone el puerto 80, que es el puerto estándar utilizado para el protocolo HTTP. HTTP es el protocolo que permite la comunicación entre los navegadores web y los servidores, y se utiliza para acceder a páginas web y aplicaciones que funcionan a través de la red.

3. ¿Cuantos contenedores incluye este proyecto?
El proyecto incluye un único contenedor. Este contenedor ejecuta la aplicación Snapdrop completa, ya que se trata de una aplicación sencilla que no depende de servicios adicionales como bases de datos externas o sistemas de autenticación separados.

4. ¿Has notado cambios en la carpeta de tu proyecto al desplegar la aplicación? Indica cuales.
Al desplegar la aplicación con Docker Compose, puede que no se produzcan cambios visibles en la carpeta del proyecto, a menos que el archivo de configuración de Docker indique que deben crearse volúmenes o directorios para almacenar archivos temporales o persistentes. Si la aplicación guarda archivos recibidos, es posible que se cree una carpeta donde se almacenen esos archivos localmente.
5. Cuando termines de responde a todas las preguntas. Haz commit de los cambios realizados con el mensaje.bnnnbmbm




