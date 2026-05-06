#traer la imagen base para python
FROM python:3.9-slim 

#establecer el escritorio de trabajo
WORKDIR /app 

# crear archivos de requerimiento en el continer
COPY requirements.txt .

# Instalar las dependencias
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application code into the container
COPY . .

# Exponer el puerto de ejecución
EXPOSE 5000


#Ejecutar la aplicación
CMD [ "python", "app.py"]