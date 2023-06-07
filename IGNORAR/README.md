## Ignorar ficheros .gitignore

## Comandos
1) touch .gitignore
2) git add .gitignore

A veces puede suceder que no queremos incluir ciertos
archivos en un commit, ya sea porque son temporales,
exponen información delicada, o simplemente no son
relevantes para el proyecto.

---

El .gitignore es un archivo especial que Git utiliza para
ignorar ciertos elementos, directorios o patrones en un
proyecto. Este archivo se coloca en la raíz del proyecto y
se le pueden añadir reglas. Es importante destacar que, los archivos que se añadan a .gitignore no se eliminarán
del sistema, sino que simplemente serán ignorados por Git a la hora de trabajar con ellos.

---

Para crear un archivo .gitignore podemos utilizar el comando touch desde la terminal o desde el propio sistema
de archivos del sistema operativo. Es importante que el
archivo lleve un punto al principio para que sea interpretado como oculto. También es esencial que se llame exactamente .gitignore. Una vez creado, se visualizará en la lista de archivos del proyecto.

---
Una vez que se ha añadido la línea al archivo .gitignore,
Git dejará de considerar el archivo < nombre_archivo > en
el área de Stage, y no se incluirá en ningún commit futuro.

---
Mecanismos:
-
Archivos por su nombre: Se puede escribir el nombre exacto del archivo que se quiere ignorar. Por
ejemplo: archivo_temporal.txt.
- Carpeta completa: Se puede escribir el nombre de
una carpeta completa que se quiere ignorar. Por
ejemplo: carpeta_temporal/.
- Patrón: Se pueden utilizar patrones que coincidan
con múltiples archivos o carpetas que se quieren ignorar. Algunos ejemplos de patrones comunes son:
– *.log: Ignora todos los archivos con extensión
.log.
– **/temp: Ignora la carpeta temp en cualquier
parte del proyecto.
- Especificar varias reglas: Se pueden utilizar múltiples
reglas en el archivo .gitignore, separadas por líneas
en blanco o por un salto de línea.

Es importante destacar que Git también soporta algunos
caracteres especiales en los patrones de los archivos que
se quieren ignorar, como el asterisco (*) para representar
cero o más caracteres, el signo de interrogación (?) para
representar un solo carácter, el signo de admiración (!)
para realizar una negación, o los corchetes ([ ]) para
especificar un conjunto de caracteres. Estos mecanismos
pueden ser muy útiles para definir patrones más específicos y detallados.

---
[Volver.](https://github.com/megagringa/Git-GitHub)