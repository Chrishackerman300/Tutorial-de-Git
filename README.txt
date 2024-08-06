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

18.- git commit -a 
    Este comando abre un archivo en nuetro editor de código y ahí le escribimos el mensaje y depués lo cerramos. Compromete todo de igual forma.

19.- rm <File>
    Este comando elimina un archivo de nuestro branch de git.

20.- git restore --staged <File>
    Este comando sirve para sacar un archivo en la etapa de stage.

21.- git restore <File>
    Este comando sirve para recuperar el archivo de stage.

22.- mv <File> <File>
    Con este comando podemos cambiar el nombre de un archivo un ejmplo sería: mv index.html proyect.html.

23.- git diff
    Con este comando vemos de una forma mas visual los cambios del archivo.

24.- git branch
    Este comando muestra la rama en la que estamos.

25.- git branch -m "Nombre Rama"
    Este comando sirve para cambiar el nombre de una rama de nuestro git.

26.- git checkout -b "Nombre Rama"
    Este comando sirve para crear una nueva y cambiarnos de rama.

27.- git checkout "Nombre Rama"
    Con este comando cambiamos a una rama ya existente.

28.- git log
    Este comando mostrara a detalle el historial de nuestro repositorio de git.

29.- git log --oneline
    Este comando mostrará la información mas importante del historial de nuestro repositorio de git.

30.- cat <File>
    Este comando mostrara el contenido del archivo.

31.- git merge "branch"
    Este comando sireve para enviar las modificaciones de un branch al branch principal.

32.- git branch -d "Nombre branch"
    Este comando eliminara una rama de nuestro branch

33.- git push origin nombre de la rama
    Este comando sirve para mandar a nuestro repositorio todos nuestros archivos creador en la rama, cuando modifiquemos un archivo existente, debemos insertarlo de nuevo a la rama.
