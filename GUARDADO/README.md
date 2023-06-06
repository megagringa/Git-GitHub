### Guardado $git add y $git commit

1) git status
2) git add < archivo >
3) git add .
4) git commit -m "< mensaje >"

---

En el repositorio se encuentra toda
la información de nuestro proyecto, incluyendo los distintos puntos de guardado que se hayan realizado. Una rama, por otro lado, es una línea de desarrollo independiente
que parte de un punto de guardado o commit.

---

### Commit

Los commits se almacenan en el historial de cambios
del repositorio y se identifican por un hash, un identificador único.

---

El comando git add nos permite añadir archivos al
área de Stage, que es una zona intermedia donde se
preparan los cambios que queremos incluir en nuestro
próximo commit. Es importante tener en cuenta que Git
solo guarda los cambios que hayan sido incluidos en el
área de Stage mediante git add.

---

 Para comprobar el estado de la rama actual, y de Git en nuestro
proyecto, usamos el comando git status. Al ejecutarlo,
nos muestra diferente información, y nos indica, por
ejemplo, que en la rama main aún no hay commits.

---

Con git add ejecutado, y siendo conscientes de los
ficheros de los que queremos tomar la primera fotografía,
lo siguiente será confirmar dicha acción.
Recordemos los comandos: git init para iniciar elrepositorio, git status para ver el estado de los archivos en la
rama, y git add para añadirlos al área de preparación
o Stage. Debemos saber que, si ejecutamos git add .,
añadiremos todos los archivos pendientes de versionar.

---

Usaremos el comando git commit -m,
seguido de un mensaje que describa de forma concisa
qué se incluye en la fotografía, por ejemplo, “Este es
mi primer commit”.

---
[Volver.](https://github.com/megagringa/Git-GitHub)