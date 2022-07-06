# Git-y-Github
Usando Git y Github

## ¿Que es Git?
Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

## Instalación
Para instalar Git solo ve a su pagina oficial [ Git ](https://git-scm.com/) y dale al boton descargar, escoge tu sistema operativo y luego da siguiente en todo, en caso estes en Windows asegurate que este seleccionada la casilla de git bash ya que es la terminal que usaremos para el uso de Git.

## Introducción a la terminal
La terminal o consola es un dispositivo electrónico o electromecánico que se utiliza para interactuar con un computador. 

Algunos Comandos Basicos para la terminal son:

> pwd: Nos muestra la ruta de carpetas en la que te encuentras ahora mismo.

> mkdir: Nos permite crear carpetas (por ejemplo, mkdir Carpeta-Importante).

> touch: Nos permite crear archivos (por ejemplo, touch archivo.txt).

> rm: Nos permite borrar un archivo o carpeta (por ejemplo, rm archivo.txt). Mucho cuidado con este comando, puedes borrar todo tu disco duro.

> cat: Ver el contenido de un archivo (por ejemplo, cat nombre-archivo.txt).

> ls: permite ver los archivos que hayan en la carpeta donde nos encontremos.

> cd: permite movernos entre directorios o carpetas.

## Introducción a Git

Le indicaremos a Git que queremos crear un nuevo repositorio para utilizar su sistema de control de versiones. Solo debemos posicionarnos en la carpeta raíz de nuestro proyecto y ejecutar el comando:

> git init

Recuerda que Git está optimizado para trabajar en equipo, por lo tanto, debemos darle un poco de información sobre nosotros. No debemos hacerlo todas las veces que ejecutamos un comando, basta con ejecutar solo una sola vez los siguientes comandos con tu información:

> git config --global user.email "tu@email.com"
> git config --global user.name "Tu Nombre"

Si por algún motivo te equivocaste en el nombre o email puedes cambiarlo de esta forma:

> git config --global --replace-all user.name “Aquí va tu nombre modificado”

O si lo deseas eliminar y añadir uno nuevo

> git config --global --unset-all user.name :Elimina el nombre del usuario
> git config --global --add user.name “Aquí va tu nombre”

## Comandos para iniciar tu repositorio en Git

```sh
git init: para inicializar el repositorio git y el staged
git add nombre_del_archivo.txt: enviar el archivo al staged
git status: ver el estado, si se requiere agregar al starget o si se requiere commit
git conf: para ver las posibles configuraciones
git conf --list: para ver la lista de configuraciones hechas
git conf --list --show-origin: para mostrar las configuraciones y sus rutas
git rm --cached nombre_del_archivo.txt: para eliminar el archivo del staged(ram)
git rm nombre_del_archivo.txt: para eliminar del repositorio
```
