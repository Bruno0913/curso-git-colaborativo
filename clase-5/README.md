# Git PAGES

En cualquier repo. Pueden habilitar un hosting para archivos estáticos.(html, .css, . js). Y pueden hospedar su sitio. (Aplicaciones Vue, React, Svelte, Angular )


Settings > Pages > Elijo el branch (rama)

Y a partir ded ahí se crea mi hosting.

### Repositorio mágico
Que automáticamente genera una git page

Nombre del repo: <usuariogithub>.github.io

Ej
Nombre del repo: Bruno0913.github.io

# Issues
Problemas que puede tener la aplicación. Se pueden crear e interactuar con la comunidad

# Pull Request
son modificaciones que esperan revisión por los dueños del repositorio. Primero tengo que hacer un fork del proyecto.

# Proyect
Puede crearse un tableron kanban (metodologías ágiles)
Creando tareas vinculadas a issues

# Wiki
Crear una wiki, documentación del proyecto

# TAGS
Me sirven para buscar las versiones o releases que correspondan a un tag. Son referencias a un commit especifico en el  tiempo

### Creo un tag en el HEAD
```bash
git tag -a v1.0.0 -m "Acá tengo la versión final v1.0.0"
```
### Creo un tag en un HASH (commit) determinado
```bash
git tag -a v0.1.0 53aa1dd -m "Acá tengo una nueva versión"
```
### Listar tags
```bash
git tag
```
### Ver información detallada del tag
```bash
git show <tag>
```

Ejemplo
```bash
git show v1.0.0
```
### Versionado semántico
https://semver.org/lang/es/

### Sube todos los tags, no recomendado (NO RECOMENDADO)

```bash
git push --tags
```

### Subir un tag en especifico

git push origin <tag>

Ej
```bash
git push origin v1.0.0
```

## GIT STASH 
Guardar en un temporal, los cambios del working directory.
Cuando realizo un stash, el proyecto vuelve al último commit.

### CReo el stash

```bash
git stash
```
### Listo el stash

```bash
git stash list
```
### Recupero el Stash
Recupera lo que tenía en el working directory desde el último stash y borra ese stash
```bash
git stash pop
```
### Borro stash

```bash
git stash pop
```

```bash
git stash pop <identificador stash>
```

### Creo una rama a partir del contenido del stash 
El stash tiene el contenido del working directory

```bash
git stash branch <nombreRama>
```

### Aplicar el último o el que yo defina.
Nota: Sin borrar el stash

```bash
git stash apply stash@{2} // Aplica el último stash sin borrarlo o el stash seleccionado
```

# Actualizar fork
 Hacen un fork y luego al pasar el tiempo se encuentran quedo desactualizado

Agrego el remoto de mi repo local
```bash
git remote add upstream <remoto del proyecto original>
```

```bash
git pull upstream <rama>
```




