# ProgramacionWeb

#Publicacion de sitio HTML
-----------------------------------------------------------------------------------------------------------------------------------------
Este Proyecto consiste en la realizacion de un HTML estatico en este caso aplicamos en un Landing Page de nuestro curriculum Vitae 
el cual es desplegado dentro de un contenedor Docker aprendido en clases utilizando el servidor web Nginx.

El objetivo de este deber es  demostrar la creación, contenedorización y distribución de una aplicación web simple mediante Docker Hub.
-------------------------------------------------------------------------------------------------------------------------------------------
📁 Estructura del proyecto
mi-sitio-docker/
│
├── index.html
├── Imagenes/
│   ├── astronauthelmet_96120.ico
│   └── Autoretrato.png
│
├── Dockerfile
├── .dockerignore
└── README.md
------------------------------------------------------------------------------------------------------------------------------------------------
Instrucciones de uso 

🔨 Construir la imagen Docker: Este es un paso muy importante para la construccion porque Docker sin una imagen no funcionaria y el contenedor
no se crearia:
docker build -t web-nginx .
--------------------------------------------------------------------------------------------------------------------------------------------------
▶️ Ejecutar el contenedor: En este paso se verifica si el contenedor funciona de forma correcta:
docker run -d -p 8080:80 tuusuario/mi-sitio-web
-----------------------------------------------------------------------------------------------------------------------------------------------------
🌍 Acceder al sitio
Abrir en el navegador:
http://localhost:8080