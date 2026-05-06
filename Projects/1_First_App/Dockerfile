#traer la imagen base para python
FROM python:3.8-slim 

#establecer el escritorio de trabajo
WORKDIR /app 

# copias el contenido del directorio actual en /app en la imagen
COPY . /app

#Ejecutar la aplicación
CMD [ "python", "app.py"]