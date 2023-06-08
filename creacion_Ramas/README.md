## Creación de ramas $git branch y $git switch

## Comandos
1) git branch
2) git branch < nombre_rama >
3) git switch < nombre_rama >
4) git checkout -b < nombre_rama >
5) git switch -c < nombre_rama >

Uno de los conceptos fundamentales de Git son las ramas,
que permiten a los equipos trabajar en diferentes flujos
de desarrollo de manera independiente y colaborativa.
En esta lección, exploraremos más a fondo el concepto
de ramas en Git, aprendiendo a gestionarlas con los
comandos git branch y git switch.

---
## Utilidad 

Las ramas en Git permiten a los equipos trabajar en
diferentes flujos de trabajo de manera independiente sin
afectar la rama principal.

---
## Cración

Para crear una nueva rama en Git, utilizamos el comando
git branch, seguido del nombre de la nueva rama.

---
## Desplazamiento

Para desplazarnos a una rama diferente, utilizamos el
comando git switch, seguido del nombre de la rama a
la que deseamos movernos.
También podemos crear una rama y desplazarnos directamente a ella. Para ello utilizamos git checkout -b o
git switch -c, seguido del nombre de la nueva rama

---
## Diferencia entre switch y checkout

 La diferencia principal entre git switch y git checkout es que git switch
está diseñado específicamente para cambiar entre ramas, mientras que git checkout tiene varias funciones,
incluyendo la capacidad de cambiar entre ramas, hash,
tags y commits.

---
## Desarrollo
Una vez que estamos en una nueva rama, podemos
trabajar en ella como lo haríamos en otra cualquiera. Por
ejemplo, podemos crear nuevos archivos, modificar los
existentes, ejecutar más comandos de Git, etc.

---
[Volver.](https://github.com/megagringa/Git-GitHub)