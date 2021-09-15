# TrabajoGrupal
 TGrupal
# Ruta hacia página estática de GitHab
 https://printronald.github.io/TrabajoGrupal/

# Ruta hacia repositorio Print Ronald Git Hab

https://github.com/PrintRonald/TrabajoGrupal

Pablo Morales: Cambio color Footer en index.html
Línea 82

Daniel Vasquez: Cambio de palabra -Contactancos +Comucaque en index.html
Línea 52 

Daniela Herrera: Cambio de imagen en productos.html 
Línea 47

Tannia Cárdenas: Cambio de título -TE LO VENDO +te lo re VENDO!
Línea 14

# Cambios 10/09/2021

Integrantes
Pablo Morales: 
Daniel Vasquez: 
Daniela Herrera:  
Tannia Cárdenas: 


Se crea carpeta js
Se crea archivo script.js

const fechaHora = new Date(); Declaración de constante para obtención de fecha
const div=document.getElementById("fechaHora"); Obtención del objeto div con ID "fechaHora"
div.innerHTML = fechaHora Asignación de valor fecha al div

<script src="./js/script.js"></script> 
Se hace el llamado al script en la linea 88 de index.html
En contacto.html linea 125
productos.html linea 107
<div id="fechaHora" class="container"></div> 


Ruta repositorio : https://github.com/PrintRonald/TrabajoGrupal

# Cambios 14/09/2021

Integrantes
Pablo Morales: 
Daniel Vasquez: 
Daniela Herrera:  
Tannia Cárdenas: 
Ronald Madariaga:

# Ruta a página de GitHub pages
 https://printronald.github.io/TrabajoGrupal/

 # Ruta hacia repositorio Print Ronald Git Hab
https://github.com/PrintRonald/TrabajoGrupal

 # Pasos para implementar Fancybox en nuestro proyecto "Te lo re vendo"

 1) Navegamos hacia la página https://fancyapps.com/fancybox/3/ 
 2) Indicamos la última versión del plugin
 3) Realizamos un incio rápido con el CDN del plugin
    3.1) Se copia y pega <script src="https://cdn.jsdelivr.net/npm/@fancyapps/ui@4.0/dist/fancybox.umd.js"></script> en el head 
        despues de nuestro script de Jquery versión 3.5.1
    3.2) De la misma página del plugin se extrae el CSS del fancybox  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/ui/dist/fancybox.css"/>
4) Se navega hacia el elemento que deseamos agregar a nuestra página web, en este caso a carrusel.
5) En carrusel se extrae el elemento que más nos convenga en el sitio, en este caso es:
   5.1) <div class="carousel">
        <div class="carousel__slide">1</div>
        <div class="carousel__slide">2</div>
        <div class="carousel__slide">3</div>
        </div>
    5.2) Extraemos el código 
    const myCarousel = new Carousel(document.querySelector(".carousel"), { 
    }); 
    Lo pegamos en el archivo js/script.js 
6) Finalmente posicionamos los códigos html y js, el primero de las líneas 37 a la 49 del archivo carrusel.html
    y el segundo archivo js/script.js de la línea 1 hasta la 4    
    
