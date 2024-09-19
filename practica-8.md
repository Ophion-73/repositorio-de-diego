¿Cómo se inicializa un repositorio en Git?
con el comando git init
git init

b. ¿Cómo creas un repositorio en GitHub?
en la pagina de tu cuenta, con el boton "new"

c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
usando el comando git remote add origin  y con el link de tu repositorio
git remote add origin [URL del repositorio]

d. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
git add, git commit con el mensaje del cambio y git push para subirlo
git add .
git commit -m "Descripción del cambio"
git push origin main

e. ¿Para qué sirve el archivo .gitignore?
para que no se suban ciertos tipos de archivos
*.log
node_modules/

f. ¿Cuál es el propósito de una rama?
trabajar en diferentes versiones de la rama sin afectar la rama principal

g. ¿Qué es una fusión?
cuando llevas el contenido de una rama a otra
 git merge nombre-de-la-rama

h. Explica los diferentes tipos de fusión que existen.
 la fusión rápida (fast-forward), se usa cuando no hay cambios en la rama principal, y la fusión normal, que crea un nuevo commit de fusión.

i. ¿Cómo puedes ver el historial de tu repositorio?
con el comando git log
git log

j. ¿Cuál es el propósito de una etiqueta?
es marcar puntos en el historial de commits, en especial, versiones
git tag -a v1.0 -m "Versión 1.0"
