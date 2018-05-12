# Curso Git

## Sesión 1
* ### Introducción
    * Problema a la hora de trabajar sin scv
    * Qué es un sistema de control de versiones
    * Sistemas de control de versiones: Subversion, Mercurial, Microsoft Foundation, Git, Bazaar...
* ### Qué es Git
    * ¡OJO! Git != Github
    * Rey indiscutible de los scv
    * Importancia fundamental en el Open Source
    * Sistema distribuido. Esto significa que podemos trabajar perfectamente sin conexión al repositorio central
    * Muy breve explicación ramas. Fundamental master
    * Repositorio -> Local y remoto
    * Repositorio remoto -> Github. Crear cuenta
* ### Uso básico de Git
    * Instalación windows, linux, mac
    * Creación de repositorio con index.html -> git init
    * Explicación directorio .git
    * Creación de repositorio vacío en github
    * Añadir archivo nuevo -> git add . / git add index.html
    * Configuración usuario:
      git config --local user.name "ejemplo"
      git config --local user.email "ejemplo@ejemplo.com"
    * Explicar directorio .git y cambio paso previo
    * Hacer commit "Primer commit"
    * Explicación buenas prácticas mensajes commits. Frecuentes, mensajes descriptivos
    * git diff
    * Enlazar repositorio local con repositorio remoto -> git remote add
    * git push origin master -> Explicar git push
    * Aprender a bajar cambios: Simular cambio en index.html mediante github
    * Hacer git pull origin master. Explicar git pull (git fetch + git merge)
    * Subir otro archivo footbar.html mediante git add, git commit

## Sesión 2
* ### Uso avanzado de git
    * gitignore -> Explicación de qué es, página con ejemplos de gitignore según framework
    * ### Ramas
        * Concepto ramas
        * git branch, git checkout
        * git checkout
        * Resolución conflicto
    * Recogiendo cable: git checkout, git reset HEAD
        * git reset HEAD~1 -> Anula último commit por completo
        * git reset --soft HEAD~1 -> Anula último commit
        * Recuperando ramas borradas: git reflog, git checkout, git checkout -b
    * Comandos extras:
        git gc, git log, git diff
    
* ### Git Desktop
    * Uso básico
    * Demostración VSCode
    * Resto de clientes visuales

## Sesión 3

* ### Introducción a Github
    * Rivales: Bitbucket, 
    * Importancia en el Open Source
    * Repositorios famosos: ruby on rails, django, bootstrap

* ### Github avanzado
    * Gist
    * Wiki
    * Issues
    * Github Projects
    * Github Pages


## Sesión 4
* ### Metodologías de trabajo en equipo
    * Trabajo en equipo
    * Funcionamiento
    * Gitflow
* ### Extras
    * Clientes visuales: Github Desktop, GitX-dev, SourceTree
    * Markdown -> Cheatsheet, README.md
    * Cómo gestiona Git VSCode
