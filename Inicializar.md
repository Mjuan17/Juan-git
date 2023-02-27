# curso de git_&_github


hola amigos.
hola amigo _h_

# Inicializar git en un directorio

lo primero es que en la terminal de
comandos git se tiene que ir al
directorio a utilizar asi
despues se pone 
git init -> esto iniciara
git en la carpeta que estemos.
## agregar cambios
despues para agregar los cambios que 
agamos en los archivos del directorio
se pone en la terminal 
git add . -> esto añadira todos los 
cambios existentes
## agregar un commit
despues at que poner 
git commit -m "mensaje del commit"

## Escoger la rama del repositorio
git branch -m main
## configurar ruta del repositorio remoto
despues se tiene que configurar la ruta
del remoto.
asi:
git remote add "origin" https:/github.com/usuario/repositorio.git
"origin" -> significa que este nombre puede ser cualquiera.

## enviar por primera vez los archivos
despues se mandan los archivos al
repositorio remoto asi, por primera vez
git push -u "origin" rama(master o main)
-> preferiblemente usar main.

## para enviar por segunda vez los archivos
## Siempre y cuando la rama no se cambie
git push -> esto mandara todos los archivos
que ayan sido enviados al commit.


## Licencias 
1. Mit License
1. Bsd 2

## Como traer los archivos del remoto al local
como descargar los archivos del remoto.
con git pull.
y esto traera los archivos al local

## ignorar archivos
### Esto se pone en el archivo .gitignore
*.extension -> le dice a git que ignore a
todos los archivos con esa extension.

carpeta -> ignorara todos los archivos de la
carpeta que pongamos el nombre.

archivo.extension -> ignorara el archivo que pongamos

!archivo.extension -> es expresion de negacion que dice que 
este archivo unicamente no lo ignore, entre todos los que tengan la misma extension.

carpeta/*.extension -> dice que ignore todos los archivos con esa extension dentro de la carpeta , pero no en las subcarpetas(
que son las que estan dentro de la carpeta especificada)

carpeta/**/*.extension -> dice que ignore todos los archivos terminados en esa extension dentro de la carpeta, y tambien dentro de sus subcarpetas.(carpetas dentro de esa)