## Configuración $git config

### Comandos

1) git config
2) git config --global user.name < nombre >
3) git config --global user.email < email >

La configuración de Git se realiza mediante dos propiedades: user.name y user.email.

---
---

Para limpiar la consola, simplemente podemos escribir clear.

---
---

Para establecer la configuración de Git, tendremos que escribir el comando git config. Lo habitual, y sobre todo cuando estamos empezando, es establecerla a nivel
global. Para ello, escribimos el parámetro --global.
Esto significará que la configuración se aplicará a nivel global a la hora de trabajar con Git dentro de nuestro
equipo , nuestro ordenador. La configuración no suele ser algo concreto para un proyecto, al contrario, se suele
usar de forma general para cualquier interacción que
realicemos con Git, independientemente del proyecto. Si establecemos que la configuración es global, va a afectar
a todo lo que se haga desde Git en la sesión de usuario de nuestra máquina.

---
Para configurar nuestro usuario escribimos git config
--global user.name, y entre comillas ponemos el nombre de nuestro usuario. Una vez hecho esto, pulsamos Enter.

---
Ahora, de la misma manera que hemos
establecido el name, configuraremos la segunda y última propiedad obligatoria, el email. Establecemos la propiedad git config --global user.email. Lo ejecutamos, y este fichero de configuración se actualizará con nombre y email.

---
[Volver.](https://github.com/megagringa/Git-GitHub)
