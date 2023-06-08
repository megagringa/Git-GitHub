## Reset y log de referencias $git reset --hard y $git reflog

## Comandos
1) git reset --hard
2) git reset --hard <hash>
3) git reflog

en este
capítulo vamos a explorar dos nuevos comandos: git
reset --hard y git reflog. Estos comandos nos permitirán manejar, aún mejor, nuestro historial de commits,
y corregir errores en caso de ser necesario.

---

## Reset —hard

El comando git reset --hard es una variante más
radical del comando git reset. Mientras que git reset
nos permitía retroceder en el tiempo hasta un punto
específico en nuestro historial de commits, con git reset
--hard podremos eliminar todo lo que se haya hecho
después del punto de retorno que le indiquemos, incluyendo los cambios no confirmados en el área de trabajo, y los commits adicionales que se hayan realizado.

---
---
---
Es importante tener en cuenta que el comando git reset
--hard es una operación peligrosa, ya que borra permanentemente cualquier cambio posterior al punto de
reseteo.

---
## Reflog

Este comando nos muestra el historial completo
de todas las acciones realizadas en nuestro repositorio,
incluidos los commits que creíamos haber eliminado con
el comando git reset --hard.

---
Para recuperar esos cambios, simplemente buscamos en
el listado el hash del commit al que queremos volver y
ejecutamos de nuevo git reset --hard con ese identificador. Esto nos llevará de vuelta al punto en el que nos
encontrábamos antes de ejecutar el git reset --hard.

---

y importante tener en cuenta que estos comandos
son operaciones peligrosas que pueden tener consecuencias graves si se usan incorrectamente.

---
Supongamos que nos damos cuenta de que los dos últimos commits son errores, y queremos eliminarlos. En
este caso, podemos usar su variante git reset --hard.
Para hacer esto, escribimos git reset --hard seguido
del hash del commit al que queremos regresar.

---
[Volver.](https://github.com/megagringa/Git-GitHub)