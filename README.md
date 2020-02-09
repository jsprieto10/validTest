
# Prueba técnica de Valid por Juan Sebastian Prieto

Los proyectos se dividen en dos, a continuación se encuentran los links
1. [Backend](https://github.com/jsprieto10/backend)
2. [Frontend](https://github.com/jsprieto10/frontend)

## Backend
En primer lugar para el backend se usó Spring boot 2, se agregaron las librerías web, h2 y jpa para el manejo de base de datos con un ORM.
Un patrón de diseño utilizado fue el de repository pues el objetivo de este patrón es separar el código relacionado con la persistencia de la lógica de negocio y también mejorar la reutilización de su código relacionado con la persistencia usando spring se diseño el backend con un patrón arquitectónico
MVC donde se puede claramente la separación con los paquetes com.valid.model (Model); com.valid.rest (View); com.valid.service (Controller) 

### Adicional
Adicionalmente se realizaron un par de actividades para darle más valor al test
1. Se realizo el despliegue del backend en internet en un servidor de heroku https://validtest.herokuapp.com/usuarios/
2. Se crearon pruebas unitarias para probar la lógica de la aplicación y la capa de persistencia

## Frontend
Aunque en el enunciado se describe un html básico, se decidió realizar un sitio web con el framework de React.js para también demostrar las habilidades de frontend básico pues si bien el puesto solicitado solo es de backend también me encuentro en la capacidad de desarrollar fullstack
 Patrones arquitectónicos por el funcionamiento de React el patrón que se usa en VC (View - Controller) pues con React no se puede manejar el modelo de datos

### Adicional
1. Se desplegó el sitio web de producción generado por React Production en firebase https://golden-frame-140905.firebaseapp.com/
2. Se intento crear una interfaz similar a la página web institucional [Ver](https://valid.com/es/)

