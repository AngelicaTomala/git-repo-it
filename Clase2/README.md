# Clase 02 - GIT

## Para visualizar ai hay cambios

```bash
git status
```

## agregar todos los cambios en el working directory

```bash
git add .
```

## hago commits de los cambios

```bash
git commit -m "Agrego carpeta clase2 con README.md"
```

## con el git commit solo me abre el editor
```bash
git commit
```

## Con el git log muestra todos los commits del mas nuevo al mas viejo
**NOTA:** Para salir presiona la **q**

```bash
git log
```

## Con el git log muestra todos los commits de manera resumida

```bash
git log --oneline
```

### Por fecha

```bash
git log --since="2021-12-28"
```

```bash
git log --after="2021-12-28"
```

```bash
git log --before="2021-12-28" --oneline
```

```bash
git log --after="2021-12-20" --before="2021-12-28" --oneline
```

## lisa las cantidades de commit que necesito, en este caso los ultimos 2
```bash
git log --oneline  -2
```

```bash
git log --oneline --decorate --all --graph
```

```bash
git push
```

GIT IGNORE
Sirve para ignorar archivos que no quiero seguir

Creo el archivo **.gitignore** en el directorio raiz y dentro coloco el nombre del archivo o la carpeta que no quiero seguir.

### GIT KEEP
Me permite seguir una carpeta vacia

Creo un archivo llado .gitkeep que lo que hace es tener en cuenta la carpeta vacio

### IMPORTANTE: forma corta de hacer un git add y un git commit
NOTA: tengo que tener todos los archivos seguidos.Si tengo alguno untraked,esos archivos no se van a comitear.
Untraked significa que no son seguidos que no esta guarado ningun cambio de esos archivos.


```bash
git commit -am "Agrego titulo para empezar con REMOTES"
```

### REMOTE

#### Lista alias de remotos

```bash
git remote
```

#### Lista alias de remotos y url
```bash
git remote -v
```

#### Lista alias de remotos y url
```sh
git remote add <nombreAlias> <url-repo>
```

#### Renombra el alias de la URL del remoto
```sh
git remote rename <nombre-antigio> <nombre nuevo>
```

#### Borrar remoto
```sh
git remote rm <alias-del-remoto>
```

Ej:

```sh
git remote rm origin
```

### Forma corta de hacer un status y ver los cambios en working diretory 
```sh
git status --short
```

## RAMAS (BRANCHES)
