## Alias $git alias

## Comandos
1) git config
2) git config --global alias.tree '<comando>'
3) git tree

A veces puede resultar difícil recordar ciertos comandos de Git, junto a sus propiedades y combinaciones.
Afortunadamente, Git nos permite crear Alias para simplificar este proceso.

---

## Alias

Para acceder a la configuración de Git utilizábamos el
comando git config junto al modificador --global, para que esta se aplique a todas las interacciones de
nuestro usuario en Git.

Para crear ese Alias con el nombre test, simplemente
lanzamos el comando git config --global alias.test
'< comando >'. Hecho esto, cada vez que necesitemos ejecutar ese comando, simplemente tendremos que escribir
git test desde la terminal.

---

La creación de Alias es solo una de las formas con que
podemos personalizar Git para adaptarlo a nuestras
necesidades.

---

A continuación, vamos a crear un Alias relacionado con
el capítulo anterior, y el comando complejo git log
--graph --decorate –all --oneline. ¿Qué nombre
le pondremos? Vamos a elegir tree, ya que nos hace
pensar en la representación de árbol de nuestras ramas.
Este nombre es totalmente personalizable. Después,
entre comillas, especificamos el comando que queremos
ejecutar y asociar. En este caso, será git config
--global alias.tree 'log --graph --decorate –all
--oneline'. Ejecutamos el comando y ya estaría creado
nuestro nuevo Alias.

---
[Volver.](https://github.com/megagringa/Git-GitHub)