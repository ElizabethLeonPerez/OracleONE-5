# Alguna notas

### Para agregar una nueva branch

'git push origin "nombre-de-la-branch"'

### Para enviar al main 

'git push origin "nombre-de-la-branch"


### Para estar al día en una branch

Se debe primero hacer un 'pull' del main(o de la branch que se busca sacar la información), luego un 'push' de la rama que se va a empujar.

### Para unir los trabajos

Se puede usar 'merge' o 'rebase' para unificar la información. 

### Para crear y entrar a una nueva branch

'git checkout -b lista'

### Para ver los commits por branch

'git log --graph'

Que git merge genera un nuevo commit, informando que hubo una mezcla entre dos branches;
Cómo traer commits de una branch a otra con git rebase
Que git rebase no genera un commit de merge, lo que simplifica nuestro log;

Opción correcta! Con el git restore deshacemos una modificación que aún no fue agregada al index o stage, o sea, antes de hacer git add. Después de agregar con git add, para deshacer una modificación, necesitamos sacarlo de este estado, con git restore --staged. Ahora, si ya hicimos el commit, el comando git revert puede salvarnos.

### Tag
Sirve para crear un "realease". Una versión estática del código creado, que puede ser descargable. 

1- 'git tag -a v0.1.0'
2- 'git push origin v0.1.0'
3- Abrir la página del repositorio de GitHub que creaste y verifica la pestaña Releases.

### 

'git log --oneline'
'git remote -v'


## Recursos 
Página cheatsheet:
https://devhints.io/git-log

Página que permite visualizar le camino de las branches
https://git-school.github.io/visualizing-git/


## Puntos a repasar

Como hacer un servidor local


## Apuntes a realizar

* Checklist de los pasos a realizar
* Infografía de ese checklist