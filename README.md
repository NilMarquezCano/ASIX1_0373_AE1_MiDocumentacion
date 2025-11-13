
# ASIX1_0373_AE1_MiDocumentacion
# Apuntes Lenguaje de Marcas
## Que es un lenguaje de marcas
Un lenguaje de marcas es un sitema para anotar un documento de manera que se pueda estructurar, formatear o enlazar contenido de manera legble tanto para humanos como para máquinas.
1. HTML (Hyper Text Markup Languaje)
2. XML (eXtensible Markup Languaje)
3. Markdown

## Git y git hub

## Git 
Git es un sistema de control de versiones distribuido de código abierto que rastrea los cambios en los archivos de un proyecto, permitiendo a los desarrolladores colaborar simultáneamente y mantener un historial de todas las versiones.

## Github
GitHub es una plataforma en la nube que se utiliza para alojar proyectos de software, permitiendo a los desarrolladores colaborar, compartir y gestionar cambios en el código de forma remota.

## Como hacer conexiones entre ellos
GitHub es una plataforma de alojamiento de código para trabajar con Git, que es un sistema de control de versiones local. Para conectar tu proyecto local (con Git) a GitHub, primero debes crear un repositorio remoto en GitHub, y luego, en la línea de comandos, usar git remote add origin <URL> para vincular tu repositorio local con la URL del repositorio de GitHub. Finalmente, usa git push -u origin main para enviar tus cambios locales a GitHub.




## Archivos Marcdown

EN archivos mardown encontramos diferentes maneras de verlos las que encontramos són:
.markdown
.md
.mkdown 
.text
.mdown

# Etiquetas basicas de Markdown
Para poder poner titulos tenemos el # que nos permite hacer titulos a textos dependiendo de lacantidad de # que haya
### Encabezados 
# #H1
## ##H2
### ###H3
#### ####H4
##### #####H5
###### ######H6

### Estilos de letra
Para que sirven los estilos de letras: 

- Mejorar la legibilidad: Un estilo de letra adecuado hace que el texto sea más fácil de leer y comprender, adaptándose al soporte (impreso o web).
- Crear jerarquía visual: Permiten diferenciar niveles de información (títulos, subtítulos, cuerpo) haciendo que el lector pueda seguir la estructura del texto de forma intuitiva.
- ...


Tenemos:
Italica: *texto* o _texto_ añadiendo dos ** o dos _ _
Negrita **texto** __texto__ añadiendo quatro **** o quatro __ __
Tachado: ~palabra~ se tacha con ~~


## Listas


Para poder crear listas encontramos dos tipos són:

### Ordenada
1. Se hace una lista añadiendo los respectivos numeros con 1. 2. 3. etc.


### Desordenada
* Son elementos
- de una 
+ lista desordenada


## Párrafos
Para crear un bloque de texto nuevo (etiqueta), se introduce una linea en blanco7

## Bloques de codigo
""html
\<html>\
\<head>\
\</head>\
\</html>\

## Enlaces
Con [] link dentro i poniendo el link donde se quiere acceder. Se puede añadir un titulo que quieres que salga pero sera opcional.

## Imagenes
Es con Inline-style: 
! añadiendo un [] con alt text dentro i el enlace de la imagen con titulo opcional tambien. 

## Tablas
se hacen con | | |
|tables| are| cool| 

## Notas al pie 
se ponen con [] y con ^1 i un uno dentro 
pie de pagina [^1]

## Lista de  verificación
seria con []A []B []C marcando con unax la que queramos 
[]A
[x]B
[]C


# INTRODUCCIÓN A HTML

HTML Hyper Text MarkUp Lenguage usado para estructurar y dar contenido de una pagina web. 

## Creación

Para la creacion de un archivo html tenemos que entrar en Visual Studio Code y agregar un archivo html (poner nombre al archivo y adjuntar un .html a este). Una vez creado este hay que poner ! para asi crear la estrucutura inicial. 

En este encontraremos el head y el body estos indican que parte es donde se puede picar codigo (body) y donde se puede modificar la imagen de la pagina web y el titulo seria el (head).

