# GIT STASH
El git stash guarda lo que está en el working directory (WD) en un area temporal.


## Crea un stash
```bash
git stash
```
## Lista 
```bash
git stash list
```
# .gitignore
Este archivo, es una blacklist de archivo. Todos los archivos que coloque dentro de el archivo ".gitignore", van a ser descartados

# GIT Log
Cuando estoy dentro del comando tengo que presionar la tecla **q** del teclado para salir

# Corregir el última descripción del commit

```bash
git commit --amend -m "Agrego lo de git log"
```
#  ADD y COMMIT todo junto 
**IMPORTANTE**Tengo que tener en el Staging AREA.
```bash
git commit -am "nombre del commit"
```
# GIT remote

ver si tengo el repo remoto configurado

```bash
git remote -v
```
### Agregar un repositorio a mi repo local
```bash
git remote {alias de su repositorio} https://github.com/Bruno0913{usuarioGit}/curso-git-colaborativo{nombreRepo/proyecto}.git
```
### Borro repositorio remoto del local
```bash
git remote rename {origin} {it} https://github.com/Bruno0913{usuarioGit}/curso-git-colaborativo{nombreRepo/proyecto}.git
```
### Borro repositorio remoto local
```bash
git remote rm {origin} https://github.com/Bruno0913{usuarioGit}/curso-git-colaborativo{nombreRepo/proyecto}.git
```

### Para lista un solo commit

git log --oneline -1

### De una fecha en particular
```bash
git log --since="2021-10-01"
git log --after="2021-10-01"
git log --before="2021-10-01"
git log --after="2021-10-01" --before="2021-10-21" --oneline
```
```bash
git log --oneline --decorate --all --graph
```
# BRANCH
```bash
git branch {nombre rama}
```
### Ejemplo
```bash
git branch dev
```

Otra forma de cambiar de rama

```bash
git checkout <rama>
```

Creo una rama y me cambio a la nueva rama
```bash
git checkout -b <rama>
```
Borrar una rama

```bash

```

