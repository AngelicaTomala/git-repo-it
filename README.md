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