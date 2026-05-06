#Traer imagen base para python
FROM python:3.8-slim

#Establecer directorio de trabajo de la imagen
WORKDIR /app

#Copiar todo lo necesario desde el directorio actual
COPY . .

#Instalar las dependencias desde el archivo de requerimientos
RUN pip install --no-cache-dir -r requirements.txt

