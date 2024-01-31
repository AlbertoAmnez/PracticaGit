● ¿Qué comando utilizaste en el paso 11? ¿Por qué?
- git reset --hard HEAD~1. Porque --hard elimina el working copy que es lo que queremos y HEAD~1 coge el ultimo commit de todos.
  
● ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
-Primeramente git reflog para ver el lista completo y asi identificar el commit que queremos y luego el mismo comando que el paso 11 pero cambiando "HEAD~1" por el numero identificativo del commit en cuestion de la lista.

● El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
-Primero git checkout styled para asegurarnos de que nos encontramos en esa rama y luego git merge main. No

● El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
-Primero git checkout styled para asegurarnos de que nos encontramos en esa rama y luego git branch htmlify. Si, se estan modificando las mismas lineas en dos ramas diferentes y el programa no puede determinar cual de ellas preservar.

● El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
--Primero git checkout main para asegurarnos de que nos encontramos en esa rama y luego git merge styled. No

● ¿Qué comando o comandos utilizaste en el paso 25?
-git log --graph --oneline --all --decorate

● El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
-Si, porque no afectaria al codigo con la diferencia que lo que hay dentro de 'title' apareceria integrado en 'main' y no de forma independiente.

● ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

● ¿Qué comando o comandos utilizaste en el paso 28?
-git stash

● ¿Qué comando o comandos utilizaste en el paso 29?
-git branch -D title

● ¿Qué comando o comandos utilizaste en el paso 30?
-git merge --no-ff title

● ¿Qué comando o comandos usaste en el paso 32?
-git checkout "numero de identificacion del commit"

● ¿Qué comando o comandos usaste en el punto 33?
-git checkout "numero de identificacion del commit"


