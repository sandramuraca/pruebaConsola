# 🔴 Comandos Git:
- git init: inica un repositorio
- git clone: crea una copia del repositorio
- git branch: lista las ramas
- git branch nuevaRama: crea una rama nueva
- git checkout nombreNueveRama: cambia a esa rama
- git check out -b nombreOtraRama: crea y nos mueve a esa rama
- git branch -d nombreDeLaRama: Elimina la rama que estoy indicando
- git status: nos muestra el estado que tenemos en nuestro directorio de trabajo
- git add archivoModificado: prepara los cambios que querramos subir
- git commit - m "mensaje": crea el mensaje con el que se subre el cambio
- git push origin rama:  pushea los cambios desde el local a la rama indicada
- git fetch: obtener los cambios que existan en el remoto y no tengo en mi local
- git merge: fusiona los cambios


# 🔴 Primer cambio en rama master
- Con pwd veo en q carpeta estoy 
- Me ubico en la carpeta donde quiero trabajar y:
    * mkdir y creo una carpeta
    * Touch index.html
    * Touch README.md
    * Git init
- Creo un repo en github.com
- En la consola:
    * git remote add origin y 
    * pego el url q me dice github ( de ese repo)
    * git remote -v me tiene q mostrar "origin url "(fetch) y "origin url"(push) ahí veo que está ok.(hago algun cambio en el index.html, algo para agregar, un h1 lo q fuera)
    * Git add .
    * Git commit -m "primer cambio"
    * Git branch -M main ( cambia de nombre la rama en la que estabamos q era master, a main, pero no crea una nueva rama, solo renombra a la que estabamos)
    * Git push origin main ( sube ese cambio al main)

# 🔴 Como crear Ramas:
- git branch: listado de ramas y sobre cual estoy trabajando
- git branch + nombreRama: crea rama
- git checkout + nombreRama: me mueve a la rama
- git checkout -b : va a crear rama y te lleva a la rama

# Como pasar los cambios a Main:
- pull request:  de que rama hacia donde van los cambios
- merge: pasa los cambios a main o 