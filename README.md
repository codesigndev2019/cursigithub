# cursigithub
curso github 

Este es un curso de git-github para llevar a cabo un upskilling utilizando esta herramienta

# git status 
Muestra el status del branch en el que nos encontramos y si hay cambios pendientes de comitear

# git add <filename>
Este comando es para agregar un archivo especifico a stage para poder hacer commit 

# git add --all 
Este comando es para agregar a stage todos los cambios que tenemos 

# git commit -m "message" 
Comando para crear un commit con el mensaje descriptivo de que se modifico

# git log 
Muestra un historial de commits realizados

# git show commitId 
Muestra el detalle del commit especificado

# git diff 
Muestra las diferencias de los archivos, los cambios en local y como esta en la version anterior

# git branch 
Muestra las ramas con las que cuento en el repositorio y me indica cual es la actual

# git branch branchName 
Me crea una rama con el nombre que se le indica

# git switch branchName 
Cambia la rama en la que quiero trabajar

# git checkout branchName
Similar a git switch

# git stash save "identificator message"
Funciona para guardar cambios y poder hacer switch entre branches sin tener que hacer commit 

# git stash list
Muestra una lista de archivos en stash 

# git stash pop stash@{#}
Retorna el/los archivos que estan en stash y lo elimina del listado (para mantener limpio y ordenado stash) hay que indicar la posision en la que se encuentra el stash