# Práctica GIT

### Sancho Ripoll, Alicia - Grupo A

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque este comando deshace el último commit y lo que hay en el Working copy. Si no fuese "--hard" mantendría lo que había en el Working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` 

Para ver el historial de los commits

`git reset --hard 78c1511` 

Para restaurar el commit con el identificador "78c1511", recupernadolo.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

Si, causó un conflicto ya que styled y merge estan en la misma posición, por lo tanto ya estaban "Already up to date", es decir que las ramas compartian los archivos actualizados.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Si, porque el archivo don-quijote.md ha sido editado en la misma linea en dos ramas distintas: la rama "styled" y la rama "htmlify".

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
 

No, no causo ningún conflicto.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph` 

Utilicé el comando "git graph", ya que este es el comando para hacerlo.

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, porque la rama title la creamos desde master, por lo que contiene los commits de master y está en la misma rama. Por lo que se podría hacer un merge fast-forward.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

Ya que esto deshace el merge sin perder los cambios realizados en el working copy.

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- *.md` o `git checkout -- don-quijote.md`  

Este comando descarta los cambios de los archivos " .md" o "don-quijote.md"

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title` 

Este comando elimina la rama title.

--
**11. ¿Qué comando o comandos usaste en el paso 30?**

`git reset --hard 79e9808` 

Este comando restaura el último merge que hemos deshecho (el del paso 26), que tiene el identificador "79e9808".

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git checkout 14f29da` 

Este comando nos lleva al commit con el identificador "14f29da" que es el commit de cuando se creó el poema.

--
**13. ¿Qué comando o comandos usaste en el punto 33?**

`git checkout 3cd07a8` 

Este comando nos lleva al commit con el identificador "3cd07a8" que es el commit de cuando le pusimos titulo al poema.

--



