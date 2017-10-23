# **Menú Vertical**

La tecnología es una herramienta muy importante para la comunicación entre personas, por ello la población a nivel mundial utilizan las famosas **redes sociales**. Aquellas que nos permiten romper la barreras de la distancia. ¿Pero por qué hablamos de ello? y ¿Qué tiene que ver con el tema principal?
Pues hay una barra muy importante que encontramos en cualquier red social o página, y son las barras de menú.
Nosotros veremos como podemos realizar una barra  dinámica, esto  permite una mejor navegación en cualquier página, en donde podemos encontrar diversidad de información en ella.

## Objetivos
* Realizar con exactitud un menú vertical.
* Manejar las distintas propiedades.
* Manejar las seudoclases.
* Colocar color .


***
## Modelo
Para poder realizar este trabajo se mostrará el modelo a replicar.

[Menú Vetical](https://fotos.subefotos.com/3b523ebdaaa3e207adb555eaa26b8351o.gif)

---
## Estructura del proyect
Esta conformada por una:
* Carpeta Menú horizontal
* Carpeta css
* Un archivo Index
* Un archivo estilo(css)

---

## Estructura de un archivo Index

```` html

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Menu Vertical</title>
    <link rel="stylesheet" href="css/main.css">
  </head>
  <body>

   <h1>MENÚ Vertical</h1>
   <nav>
     <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Sobre mí</a></li>
      <li><a href="#">Portafolio</a></li>
      <li><a href="#">Contacto</a></li>
      <li><a href="#">Noticia</a></li>
    </ul>
    </nav>
  </body>
</html>

````

----
## Código del archivo de css
---
```` css
/*Se colocará un estilo de fuente a todo el body*/
body {
font-family: sans-serif;
}

nav {
/*outline: 1px solid yellow;*/
width: 20rem;

}

ul {
/*outline: 1px solid yellow;*/
margin: 0;
padding: 0;
background-color: rgba(109, 111, 109, 0.09); /* fondo plomo*/
display: block;
list-style: none; /* quita las viñetas*/
line-height: 3rem; /* da espaciado*/
}

ul li:first-child {
background: rgb(249, 148, 15); /* fondo de la primera lista, anaranjado*/
}
ul li:first-child a {
color: rgba(255, 255, 255, 0.99); /* blanco*/
}

ul li:first-child a:hover {
color: rgba(9, 9, 9, 0.99); /* negro*/
}
ul li:first-child a:active {
color: rgba(247, 244, 244, 0.99); /* blanco*/
}


````
