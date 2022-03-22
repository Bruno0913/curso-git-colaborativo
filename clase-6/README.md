Mail de contacto : mlapeducacionit@gmail.com
o Telegram

https://medium.com/@jmz12/buenas-pr%C3%A1cticas-para-commits-5eb4c86b9a47


# Borrar y cambiar nombre de archivos desde el bash con git

git mv <nombre-original> <nombre-nuevo>

git rm <archivo>

# CHECKOUT otros usos

## Recuperar todos los archivos del último commit
```bash
git checkout -- .
```

## Traer un archivo especifico de algún punto de la historia

git checkout <hash/rama/tag> <nombre-archivo> 


# SOFT
Saca los archivos del hash indicado y todos los subsiguientes y los deja en el working directory. Ej: tengo 3 commit con cambios en un archivo que puede ser una funcionalidad. Tiene más sentido tener todo en un commit, para eso uso git reset
 --soft
```bash
git reset --soft <hash>
```

## MIXED
Es el por defecto. Si no coloco --mixed es el que hace por defecto.
```bash
git reset --mixed <hash>
```

## HARD
Este Destructivo: Peligroso, mucho cuidado.

git reset --hard <hash>

# REFLOG
Un log de las referencias de todo lo que ha sucedido en orden cronológico