# Tarer la imagen oficial de MySQL del Docker Hub
FROM mysql:8.0

#Establecer variables de entorno para MySQL
ENV MYSQL_ROOT_PASSWORD=demopassword
ENV MYSQL_DATABASE=demodb

#Copiar el script de inicializacion de la imagen Docker
COPY init.sql /docker-entrypoint-initdb.d/

