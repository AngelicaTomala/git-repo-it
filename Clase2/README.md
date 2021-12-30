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
