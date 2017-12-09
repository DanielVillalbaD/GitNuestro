#SOLUCIONES

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
*git reset --hard HEAD~1* Debido a que debíamos perder los cambios realizados en el working copy

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
*git reset --hard df90e31* Porque df90e31 es el identificador del commit en mi repositorio, podría haber 
usado HEAD@{1} con el mismo resultado.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
No, pues realmente la rama styled ya contiene todos los commits de la rama master

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
Sí, porque el archivo git-nuestro.md contiene diferente contenido en las mismas líneas

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
No, porque fue un fast forward

**¿Qué comando o comandos utilizaste en el paso 25?**
*git log --graph*

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
Sí, puesto que la rama master no contenía ningún cambio posterior a los trabajos en la rama title desde su 
creación.

**¿Qué comando o comandos utilizaste en el paso 27?**
*git reset HEAD~1*

**¿Qué comando o comandos utilizaste en el paso 28?**
*git checkout git-nuestro.md*

**¿Qué comando o comandos utilizaste en el paso 29?**
*git branch -D title*

**¿Qué comando o comandos utilizaste en el paso 30?**
1. *git reflog* para asegurarnos de hacer reset al id correcto
2. *git reset --hard [id_commit]* (id = cca8af03), también habría arrojado el mismo resultado git reset --hard HEAD@{1}

**¿Qué comando o comandos usaste en el paso 32?**
*git reset --hard [id_commit]* (id = 4d8a6b9)

**¿Qué comando o comandos usaste en el punto 33?**
*git reset --hard [id_commit]* (id = cca8af03) 
