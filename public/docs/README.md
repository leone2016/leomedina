*instalar compilador de sass
>

* compilar sass 
>npm run compile:sass

* servidor virtual (no es necesario en angular)
 
>npm install live-server -g

* actualizar servidor cada que exista un cambio

>live-server

* crear archivos .scss en una sola linea, es importante estar dentro de la carpeta que se desea 

>C:\Natours\sass\abstracts>**touch _variables.scss _mixins.scss _function.scss**

* Imagenes gratis

>https://unsplash.com

* Iconos gratis

>http://linea.io

> como usar position absolute y relative

lo explicaré con un ejemplo:

imaginemos que tenemos una sección de comentarios (listas) y queremos poner una imagen de fondo que contenga a todos esos comentarios,

En este caso la imagen de fondo (Padre)
    * Tendria la position: absolute
    
Eara los sección de comentarios
    * Tendria la opcion de position:relative;
    
con esto puedo tener una imagen de fondo, por así decirlo
