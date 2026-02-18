PROYECTO GITHUT EN CASA
1 - git init
Esto crea el repositorio local vacío y lo deja listo para empezar a agregar archivos.

2- Ahora el siguiente paso es agregar ese archivo readme.md al área de staging para que Git lo tenga en cuenta en el próximo commit.
Esto le dice a Git que quieres incluir ese archivo en tu próximo commit.

En la terminal, escribe:
git add readme.md

3-Ahora vamos al siguiente paso: crear un commit con ese archivo. Esto guarda los cambios en tu repositorio local. Ejecuta:

git commit -m "Primer commit: agregando README.md"

El mensaje entre comillas ("...") describe lo que estás guardando; puedes poner lo que quieras, pero es buena práctica que sea claro y corto.

5-Ve a GitHub
 y entra con tu cuenta.
Haz clic en New repository.
Ponle un nombre, por ejemplo: github_casa.
No marques “Initialize with a README” (porque ya tienes uno).
Haz clic en Create repository.

6- Ahora vamos a conectar tu repositorio local con GitHub. Copia y ejecuta en tu terminal este comando (reemplazando TU_USUARIO con tu nombre de usuario de GitHub):
git remote add origin https://github.com/erikbello/githut_casa.git
Esto le dice a Git que tu repositorio local tiene un “origen” remoto en GitHub.

7- Ahora vamos al último paso: subir tu commit al repositorio remoto en GitHub. Ejecuta:
git push -u origin master
origin es el nombre del repositorio remoto que acabas de agregar.
master es la rama principal (puede que tu Git use main en lugar de master; si da error, me lo dices y lo corregimos).
Después de eso, tu README.md estará visible en GitHub.



