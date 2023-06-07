## Comparación de commits $git diff

## Comandos
1) git diff
2) git diff < hash_commit_a > < hash_commit_b >
3) git diff --name-only < hash_commit_a > < hash_commit_b >

En este capítulo vamos a profundizar en el concepto de
comparación de commits y su contenido.

---
## Diff

Antes de hacer un commit, podemos utilizar el comando
git diff para examinar los cambios exactos que hemos
realizado.
En la consola, los cambios realizados aparecen con un
signo menos (-) en la línea que ha sido eliminada, y un
signo más (+) en la línea que ha sido añadida.
De esta manera, podemos llevar un control preciso de todos los cambios que hemos llevado a cabo en el proyecto.

---
## Diff entre commits

Para utilizar el comando git diff entre dos commits específicos, debemos indicar los identificadores únicos de
los commits, los llamados hash, que podemos consultar
cuando hacemos un git log. Por ejemplo, si queremos
ver los cambios realizados entre el commit < hash_commit_a > y el commit < hash_commit_b >, debemos escribir el
comando git diff < hash_commit_a> <hash_commit_b >
en la consola.

---

También podemos utilizar el comando git diff con
otros argumentos, como el parámetro --name-only, que
nos muestra solo los nombres de los archivos que han
sido modificados entre los dos commits especificados.

---
[Volver.](https://github.com/megagringa/Git-GitHub)

