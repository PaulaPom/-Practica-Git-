# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque así deshace el commit y lo que había en el Working copy

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog y git reset--hard a156f55` 

Para conseguir que don.quijote.md vuelva a tener el commit.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

`git merge master` 

Salía "already up-to-date" por lo que no se hacía nungún merge.

--
**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

`git merge htmlify, git add, git commit-m "texto del commmit"` 

Sí, por que el mismo archivo don-quijote tenía dos informaciones distintas, por lo que me he quedado con l de styled y he hecho los comndos que he puesto arriba.


--
**5.El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

`git merge styled` 

No.
 
--
**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph` 

Con esto me dibujó un diagrama.

--
**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

`git merge title` 

Sí, tendría que moverme a la rama title.

--
**8. ¿Qué comando o comandos utilizaste en el paso 27? ¿Por qué?**

`git reset HEAD~1` 

Con eso me ha deshecho el commit sin modificar el working copy.

--
**9. ¿Qué comando o comandos utilizaste en el paso 28? ¿Por qué?**

`git add don-quijote.md` 

 He vuelto a hacer un commit.

--
**10. ¿Qué comando o comandos utilizaste en el paso 29? ¿Por qué?**

`git branch -D title` 

Para borrar la branch title.

--
**11. ¿Qué comando o comandos utilizaste en el paso 30? ¿Por qué?**

`git reset --hard c155cf9`
 
Primero git reflog para saber donde ir y hacer un reset en el commit que quiero.


--
**12. ¿Qué comando o comandos utilizaste en el paso 32? ¿Por qué?**

`git checkout 9d144b0`

Primero git reflog para saber dónde ir y luego el checkout al primer commit. 


--
**13. ¿Qué comando o comandos utilizaste en el paso 33? ¿Por qué?**

`git reset --hard c155cf9` 

Git reflog y me muevo a donde se me pide.

--