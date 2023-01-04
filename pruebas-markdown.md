# Pruebas con Markdown

# Apuntes del MPVD UAH 2223 miércoles 14 de diciembre de 2022
## Encabezamiento de segundo nivel
### Encabezamiento 
#### Encabezamiento 
##### Encabezamiento 
###### Encabezamiento 

## Comentarios
<!--
     __        __                      _     _      _
     \ \      / /__    __ _ _ __ ___  | |__ (_)_ __(_)_ __   __ _
      \ \ /\ / / _ \  / _` | '__/ _ \ | '_ \| | '__| | '_ \ / _` |
       \ V  V /  __/ | (_| | | |  __/ | | | | | |  | | | | | (_| |
        \_/\_/ \___|  \__,_|_|  \___| |_| |_|_|_|  |_|_| |_|\__, |
                                                            |___/
    Ever thought about joining us?
    https://workforus.theguardian.com/careers/product-engineering/
     --->
Este es un comentario que no se va a ver:

Fundamentos Tecnológicos del Máster en Periodismo de Datos y Visualización
Universidad de Alcalá de Henares de Madrid
Apuntes y documentación de las sesiones y talleres

Herramientas básicas del entorno de trabajo para el ejercicio de periodismo de datos 
 
1)	Editor de texto (recolector de notas) 
2)	Navegador (Firefox, Google Crome)
3)	Línea de comandos (la Terminal)
4)	Git

Programación literaria: BUSCAR CONCEPTO Y PONER CITA CON LINK

Markdown es un lenguaje informático de marca ligero para la web sin la complejidad del TML. 
Tiene una sintaxis muy simple. 
Permite escribir de una forma muy rápida. 
Podemos poner encabezamientos, letras en negrilla, enlistados y bloques de código. 
Puede servir para hacer un programa de radio, para hacer una escaleta, para hacer un guión de televisión o para hacer una web.

¿Qué se utiliza en Markdown? 

Sintaxis

H1 encabezado de primer nivel #
H2 encabezado de segundo nivel ##
H3 encabezado de tercer nivel ### 
H4 encabezado de cuarto nivel ####
H5 encabezado de quinto nivel #####
H6 encabezado de sexto nivel ######

Consejos del profesor Adolfo Antón Bravo para el uso correcto de Markdown 

4 consejos:

Sean tan minuciosxs (detallistas, verborreicxs, extendidxs) como podáis, como si se lo estuvierais contando a alguien que tiene que aprender de 0.
Usad Markdown apropiadamente
Los espacios y las líneas en blanco importan
El código inserto en un texto se ha de marcar apropiadamente

Git

Es un software libre que se puede descargar en: https://www.git-scm.com/download/

Github

Es un espacio donde puedes tener un repositorio Git remoto.

Permite que el humanware tenga repositorios de páginas web.

Normalmente en un software esa parte de ‘qué es este software’ se suele por convención y por costumbre situar en un archivo que se denomina readme.md

Si vamos a cualquiera de estos repositorios a los que hay acceso

La terminación .md significa que es un archivo Markdown

Lo que hace Github es mostrar el archivo Markdown como HTML 

Github
Al darle click en el lapicero, se puede ver el código fuente del archivo

Sintaxis orgmode COMPLEMENTAR CON UN CONCEPTO MÁS CLARO DEL MODO ORG

CREAR UN REPOSITORIO

Github es un software, es una muestra pública de carpetas que hay en un ordenador y que uno puede tener en donde está trabajando en equipo conjunto. El software tiene un control de versiones. 
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

Comandos:
comando - opciones - argumentos

- ls 		enlista los archivos de una carpeta
- ls -a		enlista los archivos de una carpeta más los que están ocultos
- pwd 		dónde estoy
- mkdir 	crear un directorio
- cd 		cambiar de directorio
- cp		copiar
- whoami	quién soy
- cat		muéstrame el contenido de este archivo
- top 		carga acumulada
- q		quit/salir/exit
- echo 		repite lo que nosotros le digamos
- head		muestra la cabeza de archivos
- tail		muestra la cola de archivos
- rm		borrar




*Lorem Ipsum* **is simply dummy** text ***of the printing and typesetting industry***. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## Listados anidados
- Lorem Ipsum is simply dummy text of the printing and typesetting industry. 
- Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.
- When an unknown printer took a galley of type and scrambled it to make a type specimen book. 
  - prueba prueba prueba prueba prueba
  - máster en periodismo de datos
-  Hendrerit gravida rutrum quisque non tellus orci ac auctor augue.
  1.  Nunc sed velit dignissim sodales.
  2.  Felis donec et odio pellentesque diam volutpat commodo sed egestas.

## Enlaces
[Lorem sed risus](https://mpvd.es) ultricies tristique nulla aliquet enim tortor. Eleifend donec pretium vulputate sapien nec sagittis aliquam malesuada bibendum. Et pharetra pharetra massa massa ultricies mi. Scelerisque eu ultrices vitae auctor eu augue ut. Vestibulum lorem sed risus ultricies tristique nulla aliquet enim.

## Insertar imágenes
![Imagen](https://www.gnu.org/savannah-checkouts/gnu/emacs/images/emacs.png "Logo prueba")

## Texto citado

`Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged.` 

It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
