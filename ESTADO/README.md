## Estado $git log y $git status

### Comandos
1) git log
2) git status

---
Como hemos visto, una de las principales características
de Git es su capacidad para tomar fotografías de los
cambios realizados en el código fuente. Estas fotografías
se denominan commits, y representan una instantánea
del estado del proyecto en un momento determinado.

---

### Log

Para visualizar las fotografías realizadas en un repositorio
de Git, se utiliza el comando git log. Al ejecutarlo, Git
muestra una lista con todos los commits realizados en
el repositorio, incluyendo el hash único que identifica a
cada uno de ellos. Esta información es útil para rastrear
la evolución del proyecto y asegurarnos de que todas las
fotografías se han almacenado según lo esperado.

---

### Status

Cuando se ejecuta git status, Git muestra una lista
de los archivos modificados en el directorio de trabajo.
Estos archivos pueden, o no, haber sido seguidos por
Git. Si se han seguido, se mostrarán como cambios listos
para commit en el área de Stage. Si no se han seguido,
se mostrarán como cambios no rastreados.

---

### HEAD

-67-