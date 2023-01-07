# Git
[**Git**](https://www.git-scm.com/) es un sistema de control de versiones distribuido gratuito y de código abierto diseñado para manejar todo, desde proyectos pequeños hasta proyectos muy grandes, con rapidez y eficiencia.

Este software libre se puede descargar en la siguiente [página web](https://www.git-scm.com/download/) para su uso en MacOS, Windows y Linux/Unix

# GitHub
![Logo GitHub](https://www.drk.com.ar/2021/08/github.svg.png "GitHub")

Es una [plataforma](https://twitter.com/github) de desarrollo completa para crear, escalar y entregar software seguro. 

- ### Características 
  - Es un espacio donde puedes tener un repositorio Git remoto
  - Permite que el humanware tenga repositorios de páginas web
  - Normalmente en un software esa parte de *"qué es este software"* se suele por convención y por costumbre situar en un archivo que se denomina `readme.md`
  - La terminación `.md` significa que es un archivo Markdown
  - Lo que hace Github es mostrar el archivo Markdown como HTML 
  - Al darle click en el lapicero, se puede ver el código fuente del archivo

Sintaxis orgmode COMPLEMENTAR CON UN CONCEPTO MÁS CLARO DEL MODO ORG

CREAR UN REPOSITORIO
CREAR UN REPOSITORIO

Github es un software, es una muestra pública de carpetas que hay en un ordenador y que uno puede tener en donde e>
Github se podría considerar que es una red social de desarrolladores 
Repositorios y proyectos git
Paso 1: creación de un repositorio
Paso 2: en Github generalmente se usa el rol público (para tener repositorios privados, hay que pagar)
Paso 3: READme es un archivo 
Choose a license 
SON DE LAS TRES PIEZAS FUNDAMENTALES QUE TIENE TODO SOFTWARE, pueden estar en un archivo o estar separados
Paso 4: crear un repositorio en la linea de comandos
echo "# JulianFMartinez" >> README.md
        git init
        git add README.md
        git commit -m "first commit"
        git branch -M main
        git remote add origin https://github.com/JulianFMartinez/JulianFMartinez.git
        git push -u origin main

- Si se crean repositorio en grupo se pueden editar conjuntamente entre sus miembros.

Nomenclaturas de Comandos:

comando + opciones + argumentos

- ls            enlista los archivos de una carpeta
- ls -a         enlista los archivos de una carpeta más los que están ocultos
- pwd           dónde estoy
- mkdir         crear un directorio
- cd            cambiar de directorio
- cp            copiar
- whoami        quién soy
- cat           muéstrame el contenido de este archivo
- top           carga acumulada
- q             quit/salir/exit
- echo          repite lo que nosotros le digamos
- head          muestra la cabeza de archivos
- tail          muestra la cola de archivos
- rm            borrar
- clear         limpia y pone en blanco la terminal

Covertir Github en una página web

Una de las cosas por la que se utiliza Github es porque permite utilizar a Github no solo como repositorio, como espacio remoto de un proyecto, sino para  producir una página web.
Hay una funcionalidad en Github es convertir el contenido en página web. De esta manera se crea un subdominio.

La ruta es: Settings + Pages + Github Pages (Deploy from a branch) (seleccionar la rama main y el directorio root y Save)

url creada en Github https://mpvdes.github.io/uah2223-julianfmartinez/

