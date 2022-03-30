# EJERCICIO-DE-CLASE-2.-Ejercicios-b-sicos-de-MS-DOS
## Ejercicio 1
### 1.- Crea la siguiente estructura de carpetas:
Creamos la carpeta "D":
`md C:\D`
Dentro de esta carpeta creamos otras tres carpetas:
`md C:\D\apli`
`C:\D\prog`
`C:\D\varios`
Nos dirigimos a la carpeta "apli" y creamos más carpetas:
`cd C:\D\apli`
`md C:\D\apli\acces`
`md C:\D\apli\excel`
`md C:\D\apli\word`
Ahora creamos las carpetas dentro de estas, comenzando por "word",primero nos dirigimos ahí:
`cd C:\D\apli\word`
`md C:\D\apli\word\notas`
`md C:\D\apli\word\textos`
Seguimos creando las carpetas, esta vez las de "excel", nos dirigimos a ellas:
`cd C:\D\apli\excel`
`md C:\D\apli\excel\info`
`md C:\D\apli\excel\tablas`
Una vez creadas todas las carpetas de la rama de "Apli" terminamos creando las de la rama "Prog", primero nos dirigimos ahí:
`cd C:\D\prog`
`md C:\D\prog\basic`
`md C:\D\prog\fortran`
`md C:\D\prog\pascal`
### 2.- Sitúate en la carpeta TABLAS
Para situarnos en la carpeta "Tablas" debemos ejecutar lo siguiente:
`cd C:\D\apli\excel\tablas`
### 3.- Vuelve a la carpeta raíz
Para volver a la carpeta raíz debemos ejecutar lo siguiente: 
`cd\`
### 4.- Muestra el contenido de la carpeta PROG
Para mostrar el contenido de la carpeta "Prog" primero nos dirigimos a ella con:
`cd C:\D\prog`
Y luego ejecutar:
`dir`
### 5.- Borra la carpeta PASCAL
La eliminamos con:
`rmdir C:\D\prog\pascal`
### 6.- Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamado PRACT
Primero nos dirigimos a la carpeta Varios:
`cd C:\D\varios`
Y ejecutamos: 
`md C:\D\apli\word\Pract`
### 7.- Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL
No situamos en "Pract":
`cd C:\D\apli\word\Pract`
Y ejecutamos:
`dir C:\D\apli\excel`
### 8.- Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz
Nos dirigimos a "Tablas":
`cd C:\D\apli\excel\tablas`
Y ejecutamos:
`dir \`
### 9.- Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de VARIOS
Nos situamos en "Apli":
`cd C:\D\apli`
Y usamos:
`md C:\D\varios\Agenda`
### 10.- Borra la carpeta EXCEL
Ejecutamos:
`rmdir C:\D\apli\excel`
### 11.- Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO
Nos dirigimos a la carpeta raíz:
`cd \`
Y ejecutamos:
`md Nuevo`
### 12.- Desde PRACT muestra el contenido de WORD 
Nos dirigimos a "PRACT":
`cd C:\D\apli\word\Pract`
Y ejecutamos:
`dir C:\D\apli\word`
## Ejercicio 2
### 1.- Utilizando el editor de textos de MS-DOS, crea un archivo de texto denominado EJER.TXT,
### con el siguiente contenido, y almacénalo dentro de la carpeta TEXTOS (dentro de la estructura
### del ejercicio anterior):
No situamos en la carpeta "textos":
`cd C:\D\apli\word\textos`
Ejecutamos:
`copy con ejer.txt`
Copiamos el texto y pulsamos Ctrl + Z
### 2.- Copia el archivo EJER.TXT en AGENDA
Ejecutamos:
`COPY ejer.txt C:\D\varios\Agenda`
### 3.- Borra el archivo almacenado en la carpeta TEXTOS
Ejecutamos lo siguiente:
`del C:\D\apli\word\textos\ejer.txt`
### 4.- Añade el siguiente párrafo al archivo EJER.TXT:
Nos movemos a la carpeta dónde está el archivo:
`cd C:\D\varios\Agenda`
Usamos el siguiente comando:
`notepad C:\D\varios\Agenda\ejer.txt`
Y añadimos el texto a añadir
### 5.- Copia el archivo EJER.TXT en la carpeta BASIC
Ejecutamos lo siguiente: 
`copy C:\D\varios\Agenda\ejer.txt C:\D\prog\basic`
### 6.- Cambia el nombre del archivo almacenado en AGENDA por FICHERO.TXT
Ejecutamos lo siguiente:
`ren C:\D\varios\Agenda\ejer.txt fichero.txt`
### 7.- Mueve el archivo FICHERO.TXT a la carpeta BASIC
Ejecutamos:
`move C:\D\varios\Agenda\fichero.txt  C:\D\prog\basic`
### 8.- Abre el archivo EJER.TXT y borra la primera frase; almacena el nuevo archivo con el nombre NUEVO.TXT dentro de la carpeta BASIC
Lo abrimos con el notepad para poder editarlo:
`notepad C:\D\prog\basic\ejer.txt`
Eliminamos la primera línea y cambiamos su nombre con:
`ren C:\D\prog\basic\ejer.txt Nuevo.txt`
### 9.- Copia el archivo NUEVO.TXT en la carpeta NOTAS
Ejecutamos:
`copy C:\D\prog\basic\Nuevo.txt C:\D\apli\word\notas`
### 10.- ¿Cuántos archivos hay en la carpeta BASIC? ¿Y en NOTAS?
Al ejecutar:
`dir C:\D\prog\basic\`
Podemos ver que en basic hay 2 archivos: fichero.txt y Nuevo.txt
Al ejecutar:
`dir C:\D\apli\word\notas`
Podemos ver en notas hay 1 archivo: Nuevo.txt
## Ejercicio 3 
### 1.- Borra la carpeta ACCESS y en su lugar crea una nueva carpeta llamada ASTRO
Para eliminar la carpeta acces ejecutamos:
`rd C:\D\apli\acces`
Y para crear "Astro" ejecutamos:
`md C:\D\apli\Astro`
### 2.- Crea la siguiente estructura de subcarpetas dentro de la carpeta ASTRO
`md C:\D\apli\Astro\Historia`
`md C:\D\apli\Astro\Ciencia`
`md C:\D\apli\Astro\Historia\Datos1`
`md C:\D\apli\Astro\Historia\Datos2` 
`md C:\D\apli\Astro\Ciencia\Astro1`
`md C:\D\apli\Astro\Ciencia\Astro2`
### 3.- Sitúate en la carpeta CIENCIA y desde allí muestra el listado de archivos y subcarpetas de la
### carpeta HISTORIA
Nos situamos en la carpeta Ciencia:
`cd C:\D\apli\Astro\Ciencia`
Y ejecutamos:
`dir C:\D\apli\Astro\Historia`
### 4.- Utilizando el editor de MS-DOS crea el siguiente archivo de texto y guárdalo con el nombre TYCHO.TXT dentro de la carpeta DATOS1
Primero nos movemos a la carpeta Datos 1:
`cd C:\D\apli\Astro\Historia\Datos1`
Ejecutamos:
`copy con tycho.txt`
Y añadimos el texto
### 5.- Utilizando de nuevo el editor de textos de MS-DOS crea el siguiente archivo de texto, y guárdalo con el nombre KEPLER.TXT dentro de la carpeta DATOS2
Primero nos movemos a la carpeta Datos2:
`cd C:\D\apli\Astro\Historia\Datos2`
Y ejecutamos:
`copy con Kepler.txt`
Y añadimos el texto
### 6.- Copia los archivos TYCHO.TXT y KEPLER.TXT en la carpeta CIENCIA
Ejecutamos:
`copy C:\D\apli\Astro\Historia\Datos1\tycho.txt C:\D\apli\Astro\Ciencia`
`copy C:\D\apli\Astro\Historia\Datos2\kepler.txt  C:\D\apli\Astro\Ciencia`
### 7.- Cambia de lugar los archivos almacenados en DATOS1 y DATOS2 de forma que TYCHO.TXT quede guardado dentro DATOS2 y KEPLER.TXT en DATOS1
Para mover 'tycho' a Datos2 ejecutamos:
`move C:\D\apli\Astro\Historia\Datos1\tycho.txt C:\D\apli\Astro\Historia\Datos2`
Para mover 'kepler' a Datos1 ejecutamos:
`move C:\D\apli\Astro\Historia\Datos2\kepler.txt C:\D\apli\Astro\Historia\Datos1`
### 8.- Crea un nuevo archivo formado por la unión de los dos anteriores (sin volver a escribir el texto) y guárdalo dentro de la carpeta HISTORIA con el nombre TOTAL.TXT
Primero movemos uno de los textos a la carpeta donde está el otro:
`move C:\D\apli\Astro\Historia\Datos2\tycho.txt C:\D\apli\Astro\Historia\Datos1`
Y ahora ejecutamos:
`copy *.txt total.txt`
### 9.- Abre el archivo KEPLER.TXT almacenado en la carpeta CIENCIA y añade el siguiente texto:
Ejecutamos:
`notepad C:\D\apli\Astro\Historia\Datos1\kepler.txt`
Y copiamos el texto dentro
### 10.- Cambia el nombre del archivo anterior por el de GALILEO.TXT
Ejecutamos: 
`ren C:\D\apli\Astro\Historia\Datos1\kepler.txt galileo.txt`
## Ejercicio 4
### 1.- Crea en la carpeta raíz de la unidad A: una carpeta denominada TECINFO
Ejecutamos:
`md C:\D\tecinfo`
### 2.- Crea dentro de TECINFO el siguiente archivo de texto y llámalo HARD.TXT
Creamos el archivo texto y añadimos el texto:
`copy con C:\D\tecinfo\hard.txt`
### 3.- Crea dentro de TECINFO el siguiente archivo de texto y llámalo SOFT.TXT
Creamos el archivo de texto y añadimos el texto:
`copy con C:\D\tecinfo\soft.txt`
### 4.- Mueve el contenido de TECINFO a la carpeta APLI del disquete A utilizado para realizar los ejercicios anteriores
Nos movemos al acarpeta tecinfo:
`cd C:\D\tecinfo`
Y ejecutamos:
`move *.txt C:\D\apli`
### 5.- Crea un nuevo archivo formado por la unión de HARD.TXT y SOFT.TXT, sin volver a escribir el texto, y guárdalo en la carpeta AGENDA con el nombre ORDER.TXT
Nos movemos al directorio "apli" (dónde se encuentran los dos archivos):
`cd C:\D\apli`
Y ejecutamos:
`copy *.txt C:\D\varios\Agenda\order.txt`
### 6.- Elimina la carpeta TECINFO
Ejecutamos:
`rd C:\D\tecinfo`
### 7.- Copia a la vez los archivos HARD.TXT y SOFT.TXT en la carpeta VARIOS
Nos situamos en el directorio "apli":
`cd C:\D\apli`
Y ejecutamos:
`copy *.txt C:\D\varios`
### 8.- Cambia la extensión de los archivos contenidos en AGENDA por .TYP
Nos situamos en la carpeta "Agenda":
`cd C:\D\varios\Agenda`
Y ejecutamos:
`ren *.txt *.typ`
### 9.- Cambia la primera letra del nombre de todos los archivos del directorio APLI que empiecen por la letra C y tengan extensión DOC de forma que empiecen con la letra S
Primero nos situamos en el directorio "Apli":
`cd C:\D\apli`
En este archivo no hay ningún archivo que cumpla con los requesitos, no obstante el comando a ajecutar sería:
`ren c*.doc s*`
### 10.- Copia los archivos contenidos en la carpeta APLI que tengan extensión DOC en la carpeta AGENDA
Nos situamos en el directorio "Apli":
`cd C:\D\apli`
De nuevo, no existe tal archivo peor el comando a ejecutar sería:
`move *.doc C:\D\varios\Agenda`


