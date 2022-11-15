//Clase 11/11/22
Ejercicio 1

1- Abrir la consola e imprimir la ubicacion actual

pwd

2- Crear una carpeta llamada “ejercicios” desde la consola

mkdir ejercicios

3- Cambiar la ubicacion a la nueva carpeta que crearon.

cd ejercicios

4- Abrir la carpeta con VSCode

code .

5- En VSCode crear una carpeta “ejercicio1”

mkdir ejercicio1

6- Crear un archivo llamado README.md vacio dentro de la carpeta ejercicio1

cd ejercicio1

touch README.md

7- Configurar nombre e email globalmente en git

git config  --global user.name Thamara Farina 

git config --global user.email thamefacha@gmail.com

8- Inicializar el repositorio git desde la linea de comandos desde la carpeta ejercicios.

cd ..

git init

9- Crear un primer commit con el mensaje “Version inicial”

git add .

git commit -m 'Version inicial'

10- Agregar al README.md los comando que ejecutarion en cada paso.

11- Crear un nuevo commit con el mensaje “Agrega solucion primer ejercicio”

git add .

git commit -m 'Agrega solucion primer ejercicio’

12- Publicar  a github en un repositorio llamado nivelacion-mir

git remote add origin LINK 

git branch -M main 

git push -u origin main

13- Enviar el link al repositorio en github a su mentor/a