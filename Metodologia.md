# Metodología de la asignatura

## Creación de un repositorio

Para esta práctica final, lo primero que se tenía que hacer era crear un repositorio en la página "Pontedatos" con el nombre de usuario, en mi caso es Serchie99. Para ello, tenía que pedir acceso a esta página para poder crear un repositorio nuevo. Luego tenía que crear una carpeta en mi propio ordenador con el mismo nombre que el de mi usuario y dentro de esta, todas los archivos que desease subir. La manera más idónea era usar el comando `mkdir`, una vez clonado el repositorio con `git clone`. Gracias a esto mi carpeta del ordenador y el repositorio de *Pontedatos* quedan conectados, es decir, es un localhost que actualiza los archivos que se crean y/o se suben. Y luego, para copiar en esa carpeta las prácticas del curso he usado el comando `cp`. Una vez hecho esto, he creado el archivo "README.md" que se encarga de explicar que hay en el repositorio. Dentro de "README.md" podemos encontrar todos los enlaces a las prácticas, la metodología y el resumen del curso. 

Cuando reuní tanto las prácticas como los archivos explicativos dentro de la carpeta de mi ordenador, tuve que actualizar los cambios al repositorio de GitHub usando el comando `git status`. Esto me permitía ver si las carpetas estaban sincronizadas. Pero me salía un aviso de que en el repositorio de GitHub faltaban archivos que si existían en la carpera del ordenador. Para solucionarlo solo tuve que usar el comando `git add .`. Finalmente, usé el comando `git commit` para dar un nombre al cambio y `git push` subiendo los cambios que realicé a GitHub. Luego solo habría que comprobar que está todo subido.

## Creación de la página web

Para terminar esta práctica final se tenía que crear la página web usando la guía de Aula Global: primero había que darle al botón de "Settings" del repositorio y luego fui "Pages" para crear la página web. En segundo lugar, elegí la rama "main" y seleccioné la carpeta "root" y posteriormente elegimos el tema que queramos para nuestra página web. Después de haber guardado los cambios, fui a "gh-pages" para poder visualizar mis archivos y dentro de la misma, usar el contenido del "README.md" en el archivo "index.md". De esta menera se crea la página web finalmente. 