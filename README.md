# Comandos y configuración Git y GitHub

## Crear un nuevo repositorio

- Crear un nuevo repositorio en su cuenta de github
- Crear un archivo llamado (README.md) en su proyecto local
- Crear un archivo (.gitignore) en su proyecto local (para ignorar los archivos y carpetas)

## Inicializar un nuevo repositorio GIT
```
git init
```
## Referencia del respositotio local al repositorio remoto de (GitHub)
```
git remote add origin https://github.com/RodryGit10/m1-git-github-1.git
```
- Para verificar ejecutar los siguientes comendos:
 ```
git remote
git remote -v
```
### Finalizando
```
git add .
git commit -m "Configuracion inicial de GIT"
git push origin master
```