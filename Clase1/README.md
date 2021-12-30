# Clase 01 - GIT

# H1
## H2
### H3
##### H5

## Markdown (archivo.md)

https://www.markdownguide.org/cheat-sheet/

## Saber si tengo git instalado

**Nota:** ` = backtick => ALT + 96

```sh
git --version
```

## Comando de consola

### Limpio la consola

```sh
clear
```

### Ingreso a un directorio

```sh
cd <directorio>
```

### Retrocedo directorio

```sh
cd ..
```

### Inicializa un repositorio

```sh
git init
```

### Listar archivo en consola sin ver ocultos

```sh
ls -l
```

### Listar archivo en consola  ver ocultos

```sh
ls -la
```

### borrar la carpeta .git de forma forzada

```sh
rm -rf .git
```

## Configurar las variables de entorno inicial de GIT

#### Configuro el usuario

```sh
git config user.name "Ange"
```

#### Configuro el mail

```sh
git config user.mail "angetomala@hotmail.es"
```

## Listo las configuraciones del usuario

```sh
git config --get-regexp user
```

### Para saber lo que esta pasando en el WD
```sh
git status
```

## Paso del Working Directory (WD) al index (staged)
**IMPORTANTE:** Cuidado es case sensitive

### Preparamos el archivo

```sh
git add <nombreArchivo>
```

### Preparamos el archivo del WD al index mas de un archivo

```sh
git add .
```

### Para pasar del INDEX al Repositorio Local
```sh
git commit -m <mensaje>
```
ejemplo 

```sh
git commit -m "Agredo el README.md"
```

### 

```sh
git log
```

```sh
git log --oneline
```


### Pasos para subir mi repo local al remoto

1. git init
2. git status
3. git add README.md
4. git commit -m "first commit"
5. git remote add origin https://github.com/AngelicaTomala/git-repo-it.git
6. git push -u origin master