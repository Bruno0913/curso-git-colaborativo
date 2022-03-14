# GIT ADD

## Agregar todo lo del working directory al Staging Area o Index

```bash
git add .
```

## borre el archivo fisico del WD, para quitarlo tengo que hacer lo siguiente

```bash
git rm <nombreArchivo>
```

## Si quiero agregar archivos por separado

```bash
git add <nombreArchivo>
```

# ALIAS
```bash
git config alias.lg "log --oneline --decorate --all --graph"
git config alias.s "status"
```
## Listar Alias disponibles
```bash
git config --get-regexp alias
```

# AYUDA DE GIT en LOCAL

```bash
git help <nombreComando>
```

## Para quitar un alias o cualquier configuración que hice

```bash
 git config --get-regexp alias
 ```
 
 ```bash
 git config --unset alias.s
 ```
 ## Modifico manualmente la configuración de git
 ```bash
 git config --global -e // Abre el editor configurado por defecto en git 
 ```