# clase 03 - GIT

## listar rama
´´´sh
git branch
´´´

## Crear una rama
´´´sh
git branch clase3
´´´

## Cambiarme a la nueva rama
´´´sh
git switch clase3
´´´

## para ver los cambios que hemos realizados hacemos
´´´sh
git status
´´´

Nota cuando nos sale untracked significa que no le hemos dados segui,ientos pro lo tanto hay que hacer git add .

´´´sh
git commit -m "Agrego carpeta y Readme clase3"
´´´

## para ver que se hicieron los cambios y ya no hay mas nada para hacer commit 
´´´sh
git status
´´´

## para ver todos los commit realizados

´´´sh
git log --oneline
´´´

Nota: si realzia un nuevo cambio en la rama clase 3 hacer ya puedo realzir git commit -am

´´´sh
git commit -am "Repaso git branch"
´´´

## Git Merge

### tipos de Merge

Fast-Fodward (No hay ningun cambio que se solape con lo que esta en la otra rama)

Fast-Fodward - Union automaticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva - Uniones automaticas (No hay colisiones de cambios)

Manual - Conflictos (ocurre cuando hay modificaciones en las mismas lineas)

Nota: si deseo colocar los cambios de master a clase3 tengo que estar en clase 3 y colocar git merge master

´´´sh
git merge master
´´´

## para ver las bifurcaciones
´´´sh
git log --oneline --decorate --all --graph
´´´

## se puede hacer un abort en el caso que no se desea hacer commit
´´´sh
git merge --abort
´´´

## Alias

### crear alias

´´´sh
git config alias.lg "log --oneline --decorate --all --graph"
´´´

nota : como el alias es lg automaticamente se ejecuta el "log --oneline --decorate --all --graph"

´´´sh
git lg
´´´

## crear alias l
´´´sh
git config alias.l "log --oneline"
´´´

## ejecutar el alias l

´´´sh
git l
´´´

## para ver los alias creados

´´´sh
git config --get-regexp alias
´´´

### Para editar el archivo de configuracion de GIT

´´´sh
git config -e
´´´

## crear alias s
´´´sh
git config alias.s "status --short"
´´´

## para borrar el alias s
´´´sh
git config --unset alias.s
´´´

## GIt CLONE

creo la carpeta clone
doy click derecho y selecciono la opcion git bash here
se abre una ventaje y coloco git clone https://github.com/mlapeducacionit/git-repo-it.git
automaticamente en esa carpeta se copia todos los documentos de ese repositorio git

si quiero que cree una carpeta lllamada MeCoipieRepo coloco
 git clone https://github.com/mlapeducacionit/git-repo-it.git ./meCoipieRepo
 

 # Fork
 me permite crear un repo en mi cuenta de cualquier proyecto de GitHub
1. vamos al repo que queremos hacer el fork. Presionamos el boton.
2. Se crea el repo en mi cuenta.
3. Puedo clonar ese repo y empezar a trabajar