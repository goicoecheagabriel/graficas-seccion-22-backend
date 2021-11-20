# Backend del proyecto SECCION 22 CURSO DE ANGULAR

Para utilizar este backend utilizamos la libreria json-server para servir el db.json como un api backend.

1. Instalar la libreria de la siguiente manera
    + npm install -G json-server
2. En una terminal ejecutar la libreria con el siguinete comando. Antes del comando poner la terminal en la carpeta donde se encuentra el db.json
    + json-server --watch db.json
3. Probar el servicio con postman haciendo un `GET` a la siguiente direccion.
    + http://localhost:3000/grafica