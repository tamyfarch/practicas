# CLASE 14/11/22

Ejercicio 2 - https://www.notion.so/CLASE-14-11-22-8da1a37752af4c3a94d0f8e5574666c4

1- En el mismo repositorio del ejercicio anterior crear una rama llamada ejercicio2

git branch / para ver en que rama estamos

git branch ejercicio2 / para crear la rama

git checkout ejercicio2 / con este comando nos ubicamos sobre esa rama

2- Crear una carpeta llamada ejercicio2 dentro de la carpeta ejercicio que crearon en el ejercicio anterior.

mkdir ejercicio2mkdir

cd ejercicio2

3- Crear un archivo index.html

touch index.html

4- Agrega la estructura basica que todo documento HTML deberia tenes. El titulo de la pagina debe ser “Mi receta”

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Mi Receta</title>
  </head>
  <body>
  </body>
</html>
```

5- Crear un commit con el mensaje “Agrega el esqueleto del segundo ejercicio”

git add . 

git commit -m “Agrega el esqueleto del segundo ejercicio”

6- Utiliza las etiquetas h1, h2, img, ul, li y p para crear el contenido de la pagina segun la imagen de la siguiente diapositiva( a este proceso se le conoce como maquetacion). La imagen de la ensalada se encuentra en el siguieinte link: 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6cd5361f-f589-48c8-8246-31953d7b8ea1/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8b4bae9b-6d18-488b-b3a3-cb2b90b3b1d1/Untitled.png)

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Mi Receta</title>
  </head>
  <body>
    <h1>Receta: Ensalada</h1>
    <img src="./salad.png" alt="Ensalada"/>
    <h2>Ingredientes</h2>
    <p>Los ingredientes necesarios para preparar la ensalada son los siguientes:</p>
    <ul>
        <li>Pechuga</li>
        <li>Lechuga</li>
        <li>Tomate</li>
        <li>Cebolla</li>
        <li>Maiz</li>
    </ul>
    <h2>Preparacion</h2>
    <p>Se pican todos los ingredientes, se mezclan y listo!</p>
  </body>
</html>
```

7- Crea un commit con el mensaje “Agrega el cuerpo HTML del segundo ejercicio”

git add .

git commit -m “Agrega el cuerpo HTML del segundo ejercicio”

8- Crea un archivo llamado estilos.css, referencialo desde el HTML y agrega un estilo para cambiar el color del titulo h1. Selecciona tu color preferid utilizando un seleccionador de colores como 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a20a8e9-0e54-4b1d-bd04-86ea90fa9ca2/Untitled.png)

touch estilos.css

En el archivo estilos.css :

h1 {color: green;}

En el archivo html index.html:

<link rel="stylesheet" href="./estilos.css" /> / debajo de title

9- Crea un commit con el mensaje “Agrega estilos al segundo ejercicio”

git add .

git commit -m “Agrega estilos al segundo ejercicio”

10- Integra la rama ejercicio2 a la rama principal.

git checkout main / primero debemos posicionarnos en la rama main

git merge ejercicio2 / integramos la rama ejercicio2 al main

11- Hazle push al repositorio remoto

git branch -M main

git push origin main

12- Elimina la rama ejercicio2 del repositorio local

git branch -d ejercicio2