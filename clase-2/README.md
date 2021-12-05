# CLASE 02

# Crear repositorio GIT
Se ejecuta dentro de la raíz del proyecto que se quiere versionar
```bash
git init
```
# repositorio de forma global ,local y verificacion
git config --global user.name "BRUNO"
git config --local user.name "BRUNO FRASSINELLI"
git config --local --get-regexp user

# que pasa con el repo

git status

# que paso del working directory al staging area
git add README.md

**IMPORTANTE**: Git no versiona carpetas vacias
Para que versione la carpeta tengo que crear un archivo llamado **.gitkeep**

# Programas para versionado

GitKraken https://www.gitkraken.com/download
Github Desktop https://desktop.github.com/