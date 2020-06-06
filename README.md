# Docker-Compose y WordPress con php.ini.

Instrucciones:

1. Instalar Docker
2. Crear archivo .env (ver .env-sample)
3. Adaptar wordpress-docker/php.ini si es necesario
4. Iniciar el contenedor usando `docker-compose up -d`. Demora un par de minutos en descargar las dependencias (solo la primera vez)
5. Ir a localhost:8080 en el navegador y acceder a la página de instalación de wordpress
6. Ir a localhost:9090 para acceder a phpmyAdmin

Para tumbar el contenedor pero mantener la data en la base de datos:
`docker-compose down`
