# CLASE 02

# Crear repositorio GIT
Se ejecuta dentro de la raíz del proyecto que se quiere versionar
```bash
git init
```
# Programas para versionado

GitKraken https://www.gitkraken.com/download
Github Desktop https://desktop.github.com/
# # Repositorio de forma global ,local y verificacion
git config --global user.name "BRUNO"
git config --local user.name "BRUNO FRASSINELLI"
git config --local --get-regexp user

# Que pasa con el repo

git status

# Que paso del working directory al staging area
git add README.md < de un solo archivo

## Todos los archivos
git add .

**IMPORTANTE**: Git no versiona carpetas vacias
Para que versione la carpeta tengo que crear un archivo llamado **.gitkeep**

## Para hacer un commit
git commit
Te abre el nano y vos le pones la descripción del commit
Abre el nano, colocan la descripcion
hacen Ctrl + o, guardan los cambio
Y para salir Ctrl + x

git commit -m "mensaje"