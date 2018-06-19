 -¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, porque con este comando me sitúo en el comit inmediatamente anterior, indico --hard para que los cambios se reproduzcan en el working copy.

 -¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog, para obtener la referencia al commit que deshicimos en el paso anterior.
git reset --hard 0a0ed94 Para situarnos en el commit que deshicimos en el paso anterior.

 -El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, muestra el mensaje Already up to date. Porque el nodo de la rama styled es hijo del commit de la master.

 -El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, porque los ficheros git-nuestro.md de las ramas styled y htmlify tenían modificaciones en las mismas lineas.

 -El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque el único fichero con cambios es el fichero de la rama styled

 -¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate

 -El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, porque solo hay cambios en la rama title.

 -¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

 -¿Qué comando o comandos utilizaste en el paso 28?
git checkout -- git-nuestro.md

 -¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

 -¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset —-hard 2ece676

 -¿Qué comando o comandos usaste en el paso 32?
git reflog
El enunciado no me queda claro si es mover el head : git checkout cc6c945, o mover la rama al commit indicado que seria git reset cc6c945

 -¿Qué comando o comandos usaste en el punto 33?
git reflog
El enunciado no me queda claro si es mover el head que seria con git checkout 0f916b2 o mover la rama al commit indicado que seria git reset 0f916b2
