# CLASE 02

# Crear repositorio GIT
Se ejecuta dentro de la raíz del proyecto que se quiere versionar
```bash
git init
```
# # Repositorio de forma global ,local y verificacion
1. git config --global user.name "BRUNO"
2. git config --local user.name "BRUNO FRASSINELLI"
3. git config --local --get-regexp user

# Que pasa con el repo

git status


# Que paso del working directory al staging area
git add README.md < de un solo archivo

## Todos los archivos
git add .

## Para hacer un commit
git commit
Te abre el nano y vos le pones la descripción del commit
1. Abre el nano, colocan la descripcion
2. Hacen Ctrl + o, guardan los cambio
3. Y para salir Ctrl + x

git commit -m "mensaje"

# PASOS BÁSICOS Iniciales

hecho "# curso-git-colaborativo" >> README.md
1. git init
2. git add README.md // git add .
3. git commit -m "first commit"
4. git branch -M main
5. git remote add origin https://github.com/Bruno0913(usuario de git)/curso-git-colaborativo.git(nombre del repositor)
6. git push -u origin master

#luego de los pasos básicos

1. git status
2. git add .
3. git commit -m "descripcion del commit"
4. git push