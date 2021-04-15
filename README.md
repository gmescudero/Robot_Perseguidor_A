# Robot_Perseguidor_A
Este es un proyecto para el Máster Universitario de Automática y Robótica cuyo objetivo es el desarrollo en equipo de un robot perseguidor parte de un escuadrón

## Uso básico de Git
Generales:
* git clone <repositorio> # clona un repositorio remoto en local
* git config --global user.name "FIRST_NAME LAST_NAME"
* git config --global user.email "MY_NAME@example.com"

Aliases: permiten cambiar el nombre del comando con uno mas corto 
* git config --global alias.co checkout
* git config --global alias.br branch
* git config --global alias.ci commit
* git config --global alias.st status

Estado:
* git status # muestra los cambios realizados en local
* git log # muestra el historico de commits que se han ido haciendo en el repositorio
* git fetch # comprueba si el repositorio remoto tiene commits nuevos

Añadir cambios:
* git add <fichero (con . se añade todo)> # añade los cambios realizados al fichero en local
* git checkout <fichero (con . se revierte todo)> # revierte los cambios realizados al fichero en local
* git commit # sube los cambios al repositorio local
* git push # sube los cambios al repositorio remoto
* git pull # descarga los cambios del repositorio remoto en el local

Branches:
* git branch # muestra las ramas existentes
* git branch <nombre de rama nueva> # crea una nueva rama
* git checkout <rama> # cambia a la rama especificada
* git merge <rama> # añade los cambios de la rama especificada en la actual
* git mergetool # si aparece un fallo de mergeo se puede usar para resolver el conflicto con la herramienta por defecto

## Estándares
Para mantener el control de versiones agil y facil de inspeccionar vamos a seguir una serie de pautas:
* Clases, metodos, variables, estructuras, tipos, etc deben llevar un comentario explicativo breve (una linea es suficiente)
* Cada commit debe llevar una descripcion breve de lo que se ha añadido y el identificador de la tarea que se cubre
* El mensaje de commit debera llevar el o los identificadores las tareas que aplican
* Cada fichero/nodo del codigo debera llevar una cabecera con una descripcion breve de lo que hace, el sub-equipo encargado, etc.
* El contenido del repositorio debe ser de paquetes de ROS divididos en carpetas sin contar con binarios, logs, etc.



