## Etiquetas $git tag

##Comandos
1) git tag
2) git tag < nombre_tag >
3) git tag < nombre_tag > < hash_commit >
4) git show < nombre_tag >
5) git checkout < nombre_tag >
6) git tag -d < nombre_tag >

Una de las características
más útiles de Git es su capacidad de etiquetar puntos específicos en el historial de cambios de nuestro repositorio
utilizando tags.

---

## Tag o etiqueta

 Los tags pueden ser utilizados
para marcar versiones de una aplicación, o cualquier otro
punto importante en el historial de cambios.

---
## Creación

podemos asignar un tag a un commit concreto
utilizando git tag seguido del nombre y su hash.

---
## Visualización

Podemos utilizar el comando git tag, sin argumentos.
Esto nos mostrará una lista de todos los tags en orden
alfabético.
Si queremos ver más detalles sobre un tag específico,
podemos utilizar el comando git show seguido del nombre del tag.

---
## Desplazamiento

Los tags pueden ser utilizados para movernos rápidamente entre diferentes commits en nuestro historial de
cambios. Para hacer esto, podemos utilizar el comando
git checkout seguido del nombre del tag.

---
## Eliminación
Por último, si queremos eliminar un tag que ya no necesitamos, podemos utilizar el comando git tag -d seguido
del nombre del tag.

---
[Volver.](https://github.com/megagringa/Git-GitHub)
