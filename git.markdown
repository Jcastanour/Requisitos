# Git

## Configuraciones iniciales
Global para todos los proyectos, pero si tenemos un git init local, y queremos uno solo para ese ponerle

### Config globales
git config --global user.name ""
git config --global user.email ""

### Config local
git config user.name ""
git config user.email ""

## Iniciar repositorio
git init

## lo basico
git status
git add .
git commit -m ""

### Usar convenciones para los nombres dentro del commit
https://www.conventionalcommits.org/en/v1.0.0/

## Revisar quien ha hecho commit
- git log
- git log -- graph --decorate - all  --oneline 

## git switch
git switch -c "" (si la rama no existe la crea)
git switch main --> cambiar entre ramas

## subirlo a github
git remote add origin https://github.com/Jcastanour/Requisitos.git
git branch -M main
git push -u origin main






