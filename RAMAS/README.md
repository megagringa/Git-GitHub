## RAMAS

### Comandos

1) git config --global init.defaultBranch main

2) git branch -m main
---

### Introducción

Las ramas (llamadas branch) en Git son una de las características más poderosas de esta herramienta de control de versiones. Cuando hablamos de ramas nos referimos
simplemente a diferentes líneas de desarrollo separadas,
en las cuales podemos trabajar de manera independiente, y sin afectar el trabajo que se está realizando en
otras ramas.

---

### Ventajas

Una de las ventajas de trabajar con ramas en Git es que
podemos fusionar fácilmente los cambios de una rama en
otra.

---

Si queremos cambiar el nombre de nuestra rama principal a main, podemos ejecutar el siguiente comando: git config --global init.defaultBranch main (un nuevo
comando de configuración global de Git). Así, al crear
nuevos repositorios, la rama principal se llamará main
por defecto. Para cambiar el nombre de la rama actual
de nuestro proyecto podemos usar git branch -m main.
De esta manera, nuestra rama master pasará a llamarse
main.

---

[Volver.](https://github.com/megagringa/Git-GitHub)