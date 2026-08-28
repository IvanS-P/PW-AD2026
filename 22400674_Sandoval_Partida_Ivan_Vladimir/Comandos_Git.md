# Comandos de Git

## 1- git init
Inicializa un nuevo repositorio Git en una carpeta.
Uso:
- git init

## 2- git clone
Copia un repositorio público a la computadora local.
Uso:
- git clone https://github.com/usuario/proyecto.git

## 3- git status
Muestra el estado actual del repositorio y los archivos modificados.
Uso:
- git status

## 4- git add
Añade archivos al area de preparación
Uso:
- git add archivo.txt

## 5- git commit
Guarda los cambios preparados como una nueva versión en el historial.
Uso:
- git commit -m "Añadir nueva función"

## 6- git log
Muestra el historial de commits del repositorio.
Uso:
- git log

## 7- git diff
Muestra las diferencias entre versiones o cambios sin confirmar.
Uso:
- git diff

## 8- git branch
Crea, elimina o muestra ramas del repositorio.
Uso:
- git branch nueva-funcion

## 9- git switch
Cambia de una rama a otra.
Uso:
- git switch nueva-funcion

## 10- git merge
Combina los cambios de una rama con otra.
Uso:
- git merge nueva-funcion

## 11- git pull
Descarga cambios del repositorio remoto y los integra en la rama actual.
Uso:
- git pull

## 12- git push
Envía los commits locales al repositorio remoto.
Uso:
- git push

## 13- git fetch
Descarga información y cambios del repositorio reomto sin integrarlos.
Uso:
- git fetch

## 14- git remote
Administra las conexiones con repositorios remotos.
Uso:
- git remote -v

## 15- git stash
Guarda temporalmente los cambios sin hacer commit.
Uso:
- git stash

## 16- git reset
Mueve el estado de una rama a otro commit.
Uso:
- git reset HEAD archivo.txt

## 17- git restore
Recupera archivos desde otras versiones y descartar cambios locales.
Uso:
- git restore archivo.txt

## 18- git revert
Crea un nuevo commit que deshace los cambios de un commit anterior.
Uso:
- git revert abc1234

## 19- git tag
Crea etiquetas para marcar commits específicos.
Uso:
- git tag v1.0.0

## 20- git cherry-pick
Aplica los cambios de un commit específico sobre la rama actual.
Uso:
- git cherry-pick abc1234