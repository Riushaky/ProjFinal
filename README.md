ProyectoFinalTelemática
Este es el proyecto de telematica, con contenedores

Para comenzar esta práctica debes primero clonar el repositorio con el siguiente comando: git clone https://github.com/Riushaky/ProjFinal.git .

Para iniciar el contenedor se ejecuta el siguiente comando: sudo docker build -t proyectofinal:01 .

Para ejecutar el servicio se usa el siguiente comando: sudo docker run -it -p 80:80 proyectofinal:01 python3 app.py .
