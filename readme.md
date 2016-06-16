* 11) He utilizado el comando *git reset --hard HEAD~1* ya que este nos mueve HEAD permitiéndonos variar nuestro working copy.

* 12) He sacado el listado de movimientos entre commits con *git reflog* para posteriormente con el identificador del commit al que quiero llegar, introducirlo junto al comando *git reset --hard <commit_name>*

* 13) No, no causó conflicto ya que ambas ramas <strong>pertenecen a la misma lista</strong>, y simplemente con avanzar un commit la rama master se unirá a la rama styled.

* 19) Sí, Generó conflictos ya que el archivo *git-nuestro.md* cambiaba desde una rama a otra, entonces Git nos pide que arreglemos los conflictos y hagamos un commit, cosa que hicimos quedándonos con el contenido de la rama styled.

* 21) No causó conflictos ya que la rama styled contiene a la rama master y esta rama sólo tendría que avanzar haciendo un merge ff.

* 25) He utilizado el comando *git log --graph --decorate --pretty=oneline* que lo he guardado como un comando personalizado llamado *git graph*

* 26) Sí, podría haber sido un merge no fast forward ya que title y master pertenecen a la misma línea de commits, de echo si no le hubiésemos especificado que queríamos un merge no ff nos hubiera hecho uno que sí hubiera sido ff.

* 27) Use el comando *git reset HEAD~1* para no perder los cambios en el working copy.

* 28) Usé el comando *git-checkout*  -- git nuestro.md

* 29)Usé el comando *git branch -D title*.

* 30) Con la lista de movimientos entre commits (mediante el comando *git reflog*) nos movimos al que estábamos antes del merge, después mostrando el gráfico con *git --graph* comprobamos que lo hemos hecho bien.

* 32) Use el comando *git reflog* para sacar la lista de movimientos entre commits, y apuntando hacia el primer commit de todos usé *git reset --hard* 

* 33) Como anteriormente sólo habiamos movido el HEAD hacia el commit inicial, ahora simplemente haciendo un *git checkout master* nos moveremos a la rama master que se encuentra en el final.



