<<<<<<< HEAD
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

Fast-Fodward (NO hay ningun cambio que se solape con lo que esta en la otra rama)
