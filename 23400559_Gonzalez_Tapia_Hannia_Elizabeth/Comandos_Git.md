Comando: git init
Descripción: Crea un nuevo repositorio de Git en la carpeta donde estamos trabajando. Esto permite que Git comience a controlar los cambios de nuestro proyecto.
Ejemplo: Si comenzamos un proyecto web nuevo, entramos a la carpeta del proyecto y usamos git init para comenzar a utilizar Git.

Comando: git clone URL
Descripción: Copia un repositorio que ya existe, por ejemplo uno de GitHub, a nuestra computadora.
Ejemplo: Si queremos descargar un proyecto de GitHub para trabajar con él, podemos usar git clone https://github.com/usuario/proyecto.git.

Comando: git status
Descripción: Muestra el estado actual del repositorio. Indica qué archivos fueron modificados, cuáles son nuevos y cuáles están preparados para realizar un commit.
Ejemplo: Después de modificar un archivo HTML, podemos usar git status para comprobar qué cambios detectó Git.

Comando: git add nombre_archivo
Descripción: Agrega un archivo al área de preparación (staging) para que sus cambios puedan guardarse en el siguiente commit.
Ejemplo: Si modificamos index.html, podemos escribir git add index.html para preparar ese archivo.

Comando: git add .
Descripción: Agrega todos los archivos nuevos y modificados de la carpeta actual al área de preparación.
Ejemplo: Si modificamos varios archivos de nuestro proyecto web, podemos usar git add . para preparar todos los cambios al mismo tiempo.

Comando: git commit -m "mensaje"
Descripción: Guarda los cambios que fueron agregados al área de preparación y crea un registro en el historial del proyecto.
Ejemplo: Después de terminar una modificación en una página web, podemos usar git commit -m "Agrega página principal" para guardar ese cambio.

Comando: git log
Descripción: Muestra el historial de commits realizados en el proyecto, incluyendo información como el autor, la fecha y el mensaje del commit.
Ejemplo: Podemos usar git log para revisar qué cambios se han guardado anteriormente en nuestro proyecto.

Comando: git diff
Descripción: Muestra las diferencias entre los archivos que tenemos actualmente y la versión anterior que estaba registrada en Git.
Ejemplo: Si modificamos un archivo CSS y queremos saber exactamente qué líneas cambiamos, podemos utilizar git diff.

Comando: git branch
Descripción: Permite mostrar, crear y administrar las ramas de un repositorio. Las ramas permiten trabajar en diferentes cambios sin afectar directamente la rama principal.
Ejemplo: Podemos crear una rama llamada desarrollo para trabajar en una nueva función de nuestra página web.

Comando: git switch nombre_rama
Descripción: Permite cambiar de una rama a otra dentro del repositorio.
Ejemplo: Si estamos en main y queremos trabajar en la rama desarrollo, usamos git switch desarrollo.

Comando: git checkout nombre_rama
Descripción: Permite cambiar entre diferentes ramas del repositorio. También puede utilizarse para recuperar versiones anteriores de archivos.
Ejemplo: Podemos utilizar git checkout desarrollo para cambiar de la rama principal a la rama de desarrollo.

Comando: git merge nombre_rama
Descripción: Combina los cambios realizados en una rama con otra rama.
Ejemplo: Si terminamos una función en la rama desarrollo, podemos utilizar git merge desarrollo desde main para integrar esos cambios.

Comando: git remote
Descripción: Permite administrar las conexiones entre nuestro repositorio local y los repositorios remotos, como los que se encuentran en GitHub.
Ejemplo: Podemos usar git remote para comprobar si nuestro proyecto está conectado a un repositorio remoto.

Comando: git remote -v
Descripción: Muestra las direcciones de los repositorios remotos que están conectados con nuestro proyecto local.
Ejemplo: Podemos utilizar git remote -v para comprobar a qué repositorio de GitHub está conectado nuestro proyecto.

Comando: git push origin main
Descripción: Envía los commits que tenemos en nuestro repositorio local hacia un repositorio remoto, como GitHub.
Ejemplo: Después de realizar un commit, podemos utilizar git push origin main para subir los cambios de nuestro proyecto a GitHub.

Comando: git pull
Descripción: Descarga los cambios que existen en el repositorio remoto y los integra con nuestro repositorio local.
Ejemplo: Si un compañero modificó el proyecto y subió los cambios a GitHub, podemos utilizar git pull para actualizar nuestra copia.

Comando: git fetch
Descripción: Descarga la información y los cambios que existen en el repositorio remoto, pero no los combina automáticamente con nuestra rama actual.
Ejemplo: Podemos utilizar git fetch para revisar si existen cambios nuevos en GitHub antes de incorporarlos a nuestro proyecto.

Comando: git reset
Descripción: Permite deshacer ciertos cambios o quitar archivos del área de preparación, dependiendo de cómo se utilice el comando.
Ejemplo: Si agregamos un archivo con git add por error y todavía no hacemos el commit, podemos utilizar git reset para quitarlo del área de preparación.

Comando: git rm nombre_archivo
Descripción: Elimina un archivo del proyecto y también le indica a Git que deje de realizar el seguimiento de ese archivo.
Ejemplo: Si ya no necesitamos un archivo llamado prueba.html, podemos utilizar git rm prueba.html.

Comando: git tag nombre_etiqueta
Descripción: Permite crear etiquetas para identificar versiones importantes o específicas de un proyecto.
Ejemplo: Cuando terminamos la primera versión de una página web, podemos utilizar git tag v1.0 para identificar esa versión.


