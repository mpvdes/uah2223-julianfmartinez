# Git
[**Git**](https://www.git-scm.com/) es un sistema de control de versiones distribuido gratuito y de código abierto diseñado para manejar todo, desde proyectos pequeños hasta proyectos muy grandes, con rapidez y eficiencia.

Este software libre se puede descargar en la siguiente [página web](https://www.git-scm.com/download/) para su uso en MacOS, Windows y Linux/Unix

# GitHub
![Logo GitHub](https://www.drk.com.ar/2021/08/github.svg.png "GitHub")

Es una [plataforma](https://twitter.com/github) de desarrollo completa para crear, escalar y entregar software seguro. GitHub es un software, es una muestra pública de carpetas que se tienen en un ordenador y que el humanware puede tener certeza en donde se está trabajando de forma individual o en equipo conjunto. Este software tiene un control de versiones. 

- ### Características 
  - Github se podría considerar que es una red social de desarrolladores 
  - Es un espacio donde puedes tener un repositorio Git remoto
  - Permite que el humanware tenga repositorios de páginas web
  - Normalmente en un software esa parte de *"qué es este software"* se suele por convención y por costumbre situar en un archivo que se denomina `readme.md`
  - La terminación `.md` significa que es un archivo Markdown
  - Lo que hace Github es mostrar el archivo Markdown como HTML 
  - Al darle click en el lapicero, se puede ver el código fuente del archivo

- ### Crear un repositorio o proyecto en Github

`Paso 1:` Creación de un repositorio

`Paso 2:` En GitHub, generalmente se usa el rol público (para tener repositorios privados, hay que pagar)

`Paso 3:` READme.md es un archivo (Choose a license)

`Paso 4:` Crear un repositorio en la linea de comandos
```

echo "# JulianFMartinez" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/JulianFMartinez/JulianFMartinez.git
        git push -u origin main
``` 
- ### Nomenclaturas de Comandos:

- ###### comando + opciones + argumentos
  - `ls`            enlista los archivos de una carpeta
  - `ls -a`         enlista los archivos de una carpeta más los que están ocultos
  - `pwd`           dónde estoy
  - `mkdir`         crear un directorio
  - `cd`            cambiar de directorio
  - `cp`            copiar
  - `whoami`        quién soy
  - `cat`           muéstrame el contenido de este archivo
  - `top`           carga acumulada
  - `q`             quit/salir/exit
  - `echo`          repite lo que nosotros le digamos
  - `head`          muestra la cabeza de archivos
  - `tail`          muestra la cola de archivos
  - `rm`            borrar
  - `clear`         limpia y pone en blanco la terminal

- ### Covertir GitHub en una página web
  - Una de las cosas por la que se utiliza GitHub es porque permite utilizarla, no solo como repositorio, como espacio remoto de un proyecto, sino para producir una página web.
  - Hay una funcionalidad en Github es convertir el contenido en página web. De esta manera se crea un subdominio.

La ruta es: `Settings` + `Pages` + `Github Pages` (Deploy from a branch) (seleccionar la rama main y el directorio `root` y `Save`)

De esta manera, queda una `url` creada en Github https://mpvdes.github.io/uah2223-julianfmartinez/

