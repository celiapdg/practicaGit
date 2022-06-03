## Ejercicio 7. Práctica Git

para el clonado `git clone https://github.com/DavidBernalGonzalez/practicaGit.git`

para cambiar el repositorio remoto `git remote set-url origin https://github.com/celiapdg/practicaGit`

creo una rama y directamente me muevo a ella en un solo comando: `git checkout -b nuevaRama`

Para moverme a una rama existente uso `git checkout nombreRama`

Cada vez que quiero registrar los cambios, uso `git add .` y `git commit -m "mensaje"` y si además quiero subirlos al repositorio remoto, uso `git push -u origin nombreRama`

Para fusionar ramas, me muevo a la rama de destino y hago `git merge otraRama`

Para poder ver todas las ramas `git branch -a`