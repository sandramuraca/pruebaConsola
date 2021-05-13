# Primer cambio en rama master

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
    * git remote -v me tiene q mostrar "origin url "(fetch) y "origin url"(push) ahí veo que está ok.
(hago algun cambio en el index.html, algo para agregar, un h1 lo q fuera)
    * Git add .
    * Git commit -m "primer cambio"
    * Git branch -M main ( cambia de nombre la rama en la que estabamos q era master, a main, pero no crea una nueva rama, solo renombra a la que estabamos)
    * Git push origin main ( sube ese cambio al main)