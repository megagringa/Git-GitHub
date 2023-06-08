## Desplazamientos en una rama

## Comandos
1) git checkout < hash >
2) git checkout HEAD

Una de las características más importantes de Git es su
capacidad para realizar el seguimiento de cambios en el
código, y permitirnos desplazarnos a través de diferentes
versiones del mismo. 

---

Si escribimos el hash del primer commit después de git
checkout, algo así como git checkout 0000000, siendo
0000000 el hash correspondiente, Git nos avisará de que
podríamos perder los cambios que no hemos guardado
antes de llevar a cabo el desplazamiento. Al hacerlo,
nuestro editor indica que algunos archivos han sido eliminados, pero en realidad, nos hemos movido a un estado
anterior del proyecto.

---

Para regresar al estado actual de nuestro proyecto,
podemos usar git checkout HEAD. Al hacerlo, nos
desplazamos al extremo final de la rama actual. Podemos
revisar en el git log que hemos cambiado nuestra
posición en el historial de commits. Otra manera de
movernos al final de la rama, es simplemente haciendo
git checkout seguido del hash abreviado del último
commit.

---

Con git log, podemos comprobar cómo nuestro
proyecto puede identificar los commits, y movernos
entre ellos usando solo la parte final del hash. Al ejecutar
git tree (creamos anteriormente un Alias para este
comando), observamos que el puntero dentro de la
rama main está en el último commit, al igual que HEAD.
Nuestros últimos archivos han vuelto a aparecer en
nuestro proyecto local.

---
[Volver.](https://github.com/megagringa/Git-GitHub)
