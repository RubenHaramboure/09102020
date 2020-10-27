# Trabajo_1eva 
## <span style= "color:#28FBF6">***INTRODUCCIÓN A GIT***</span>


Para comenzar con los comando git, lo primero de todo, y mas principal, habrá que saber que es GIT, pues bien;

GIT es una pieza de tecnología diseñada para rastrear y registrar cambios y alteraciones en cualquier tipo de archivos, en otras palabras, GIT se utiliza  para administrar el flujo de su trabajo y seguir el progreso de varios proyectos diferentes. 

Dentro de GIT nos encontramos con repositorios; un repositorio simple y un directorio de trabajo:

- **Repositorio simple**: cuando nos referimos a un repositorio simple lo que queremos decir es que en su interior no existe ningún archivo de trabajo
- **Directorio de trabajo**: Seria lo opuesto que el repositorio simple, en el interior de este se encuentran todos los archivos

A continuación, se observarán los comandos de GIT más comunes con su correspondiente explicación:

- <span style= "color:yellow">**GIT Config**</span>: Primero de todo tendremos que vincular nuestra cuenta de GIT con nuestro ordenador de trabajo, para ello se debera de teclear lo siguiente-> *git config --global user.email example@example.com*, una vez configurado el correo tendremos que insertar nuestro nombre de cuenta mediante *git config --global user.name username*.

Una vez configurada nuestra maquina procederemos a iniciar y a urilizar GIT

- <span style= "color:yellow">**GIT Init**</span>: Con este comando lo usaremos para crear un nuevo repositorio de GIT, la base principal de todo proceso GIT
- <span style= "color:yellow">**GIT Add**</span>: Este comando se usa para añadir archivos como por ejemplo un .txt y utilizariamos *git add trabajo.txt*
- <span style= "color:yellow">**GIT Commit**</span>: Se usa para cambiar la cabecera, cualquier cambio realizado aquí no se verá afectado nuestro repositorio, se recomienda su uso despues de hacer un git add, tendremos que utilizarlo de esta manera: *git commit "primer commit* asi sucesivamente cada vez que añadamos algo nuevo apra tenerlo todo controlado y con un orden coherente.
- <span style= "color:yellow">**GIT Status**</span>: Nos muestra los archivos que han sido cambiados junto con los archivos que están por añadir, será necesario introducirlo de esta forma *git status -s* al contrario, no nos funcionaria en nuestra maquina
- <span style= "color:yellow">**GIT Push**</span>: Mediante este comando enviaremos todo el trabajo realizado a nuestro servidor que estemos utilizando
- <span style= "color:yellow">**GIT Branch**</span>: Se utiliza para crear o borrar ramas para crearla unicamente debemos poner *git branch /nombre rama/* pero para borrarla deberemos utilizar *git branch -d /nombre rama/* 
- <span style= "color:yellow">**GIT Checkout**</span>: Se utiliza para cambiar entre ramas o crearlas, por ejemplo mediante este comando nos crea una nueva y nos cambia a ella directamente -> *command git checkout -b /branch name/*, pero si unicamente queremos cambiarnos utilizaremos *git checkout /branch name/*
- <span style= "color:yellow">**GIT Remote**</span>: Se utiliza para conectar a un repositorio remoto, mediante el siguiente comando nos mostrará cuales están configurados *git remote -v*
- <span style= "color:yellow">**GIT Pull**</span>: Este comando se usa para fusionar todos los cambios realizados en el repositorio local que se está trabajando.
- <span style= "color:yellow">**GIT Merge**</span>: Se usa para fusionar una rama con otra rama activa, si tenemos dos ramas llamas Rama1 y Rama2 y queremos fusionarlas en la Rama1, primero nos colocaremos en la Rama1 y a contiuación usaremos *git merge Rama2* y se nos juntarán ambas ramas en una sola.
- <span style= "color:yellow">**GIT Diff**</span>: Será necesario para hacer una lista de los conflictos obtenidos, para poder ver esos conflictos teclearemos *git diff --base /nombre archivo/* pero si unicamente queremos que nos englobalice los conflictos ponemos *git diff* y listo.
- <span style= "color:yellow">**GIT Reset**</span>: Para resetear el directorio que se está trabajando al último estado comprometido, se usa el siguiente comando *git reset --hard head*
- <span style= "color:yellow">**GIT rm**</span>: Este comando se utiliza para remover archivos del directorio en el que se está trabajando.
- <span style= "color:yellow">**GIT Fetch**</span>: Se utiliza para buscar todos los objetos de un repositorio que actualmente no se encuentra donde estamos trabajando 
- <span style= "color:yellow">**GIT Rebase**</span>: Se utiliza para integrar cambios de una rama a otra
- <span style= "color:yellow">**GIT mv**</span>: Sirve para renombrar archivos.
- <span style= "color:yellow">**GIT Stash**</span>: Se usa para almacenar todo lo que estás trabajando en un stash y saltar rápidamente a otra parte del proyecto, sin temor alguno de perder ningún archivo
