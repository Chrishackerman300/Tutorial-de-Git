#######       Curso Git #######

-¿Qués es Git?

Git es un software de control de versiones, donde podemos actualizar las versiones de nuestros proyectos de trabajo,
como una app, una web o un video juego. Principlamente se trabaja utilizando la (Git Bash) que es la propia termina de Git.

Git se utiliza es la mayoria de las empres TEC o que tengan su propio departamente de TEC.

-Comando Importantes de Git Bash

1.- git --version 
    Este comando nos mostrara la versión mas reciente de git.

2.- git config --global
    Este comando mostrara toda la información global de git.

3.- git config --global user.name "nameUser"
    Este comando lo utilizamos para poder configurar git con nuestro nombre.

4.- git config --global user.email "emailUser"
    Este comando lo utilizamos para poder configurar git con nuestro correo electronico(email).

5.- git config --global core.editor "code --wait"
    Con este comando configuraremos git a nuestro editior de código en mi caso utilizó (VSCode).

6.- ls 
    Este comando nos mostrara un listado completo de todo nuestro directorio, tanto archivos y carpetas, dependiendo en que parte del directorio 
    estemos de nuestro ordenador.

7.- pwd
    Este comando nos mostrara la dirección del directorio en el que estamos

8.- cd 
    Este comando es para cambiar de directorio (change directory) este se utiliza ingresando cd y en seguida el nombre de la ruta a la que queremos acceder,
    un ejemplo sería: cd /Desktop. Nos cambiamos al Escritorio del ordenador.

9.- cd ..
    Este comando sirve para salir de una carpeta en el directorio.

10.- mkdir
    Este comando crea una nueva carpeta en dicho directorio en el que estemos, un ejemplo sería : mkdir Nueva carpeta.

11.- git init
    Este comando es importante, con este comando ceraremos un nuevo respositorio de git en dicha carpeta en al que estemos.

12.- cd .git
    Este comando sirve para acceder a nuestro respositorio de git.

13.- git status
    Este comando mostrará el estatus de nuestro repositorio y toda su info.

14.- git status -s
    Este comando es lo mismo que el anterior pero solo nos muestra los archivos que están o aún no están en la etapa de stage.

15. git add <File>
    Este comando agrega el archivo con un nombre en específico a la etapa stage de nuestro repositorio de git.

16.- git add .
    Este comando agrega todos los archivos dentro de nuestra carpeta al repositorio de git. (No se recomienda utilizar este).

17.- git commit -m "Comment"
    Este comando compromete el archivo de la etapa de stage y lo sube a nuestro repositorio, es nesario ponerle un mensaje.