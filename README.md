# Practica-del-curso-git-github-y-sourcertree
- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
Comando: git reset --hard HEAD~1 
porque: este comando me permite cambiar el working copy por la version anterior y tambien cambia la etiqueta se desplaza hacia al anterior commit.


- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Comando: git reflog, git reset --hard <numero de identificacion del comit>
porque: git reflog nos muestra donde estubo el puntero HEAD con esto ponemos encontrar el ultimo numero de identificacion donde estubo en este caso el commit anterior y al dar git reset --hard <numero de identificacion del comit> la etiqueda con HEAD  van a pasar a este restaurando el commit.


- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
no ya que todo lo que tenia styled estaba contenido en la rama master por lo cual la abosrvio sin ningun problema


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
si porque las lines de codigo se encontraban en el mismo lugar por lo cual git no sabia cual tomar.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
no ya que como styled tenia todo lo que tenia la rama master por lo cual solo era mover la etiqueta de master a styled 

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph para que se mueste en diagramas 

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
si porque las lineas de codigo no se sumplantan unas a otras entonces git puede crear la union de las dos.


- ¿Qué comando o comandos utilizaste en el paso 27?
comandos: git reset HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
git checkout master
- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog, git reset <nombre de identificacion de commit que quiero recuperar>
- ¿Qué comando o comandos usaste en el paso 32?
git reset --hard HEAD~1 *3

- ¿Qué comando o comandos usaste en el punto 33?
git reflog, git reset <nombre de identificacion de commit que quiero recuperar>