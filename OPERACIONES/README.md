## Operaciones con ramas $git checkout y $git reset

## Comandos

1) git checkout <archivo>
2) git reset
3) git log --graph
4) git log --pretty=oneline
5) git log --decorate
6) git log --graph --pretty=oneline --decorate

Vamos a explorar por una parte los nuevos comandos
git checkout y git reset, que nos permitirán.

---

## Checkout

Este comando nos
permite situarnos en un punto específico del historial de
commits o de un archivo.
Por ejemplo, si deseamos volver al estado previo de
un archivo antes de modificarlo, podemos ejecutar el
comando git checkout < archivo >.
Este comando nos llevará al estado previo de dicho
archivo, correspondiente a la última fotografía tomada
en la rama actual.

---

## Reset 
Si deseamos volver a la última fotografía completa
tomada, podemos escribir git reset. Al lanzar este
comando se nos informará de que se perderán los
cambios en los archivos que no forman parte de un
commit.

---

## Visualizaciones
Este comando nos mostrará una lista de todos los commits que se han realizado en el proyecto, junto con información detallada sobre quién hizo los cambios, cuándo
se hicieron, y qué archivos se modificaron.

- Si deseamos revisar el historial de commits de una
manera más visual, podemos usar el comando git
log --graph. Este comando nos mostrará una representación gráfica de las ramas (cómo se dividen,
y cómo se relacionan entre sí) y los commits del
proyecto.
- Si queremos ver el historial de commits de una manera más simplificada, podemos usar el comando git
log --pretty=oneline. Este comando te mostrará
una vista rápida de cada commit en una sola línea.
Podremos consultar rápidamente el hash del commit
y el mensaje de confirmación desde una vista compacta.
- También podemos utilizar el comando git log
--decorate para consultar información adicional
sobre los commits. Este comando nos permite
visualizar rápidamente la línea de progreso
de nuestra rama y sus etiquetas (un concepto
que veremos más adelante) sin mostrar el hash
completo.

Por supuesto, puedes combinar todas las propiedades
nombradas: git log --graph --pretty=oneline
--decorate.

---
[Volver.](https://github.com/megagringa/Git-GitHub)

