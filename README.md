Proyecto Innovatech Chile
Este es nuestro proyecto final de DevOps. Creamos una página web que funciona con microservicios y se despliega automáticamente en la nube de AWS.
¿Cómo está armado?
El sistema se divide en 3 partes que trabajan juntas:
Frontend: La cara de la página (lo que ve el usuario). Hecho con React.
Backend: Los cerebros que procesan todo. Son dos servicios: Ventas y Despachos, hechos con Spring Boot.
Base de Datos: Un servidor MySQL donde se guarda toda la información.
Herramientas usadas
Docker: Para meter cada parte en un "contenedor" y que funcione en cualquier lado.
AWS (Amazon Web Services): Para que la página esté en internet (usamos EC2 y ECR).
GitHub Actions: Para que, cuando subamos código nuevo, se actualice solo en la nube.
Cómo hacerlo funcionar
Si tienes Docker instalado, solo tienes que usar este comando en la carpeta principal:

docker-compose up -d