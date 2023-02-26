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
