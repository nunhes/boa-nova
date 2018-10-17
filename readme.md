# Pasos básicos con Git

## Crear repositorio
1. Crear un novo cartafol (make directory)
<code> mkdir <NOMBEDACARPETA> </code>

2. (ou) Ir a un cartafol existente (change directory)
<code> cd <NOMBEDACARPETA> </code>

3. Lista os contidos dun cartafol
<code> ls </code>

4. Iniciar Git nun cartafol
<code> git init </code>
Este é o comando que inicia o seguimento ;)

## Facendo os primeiros cambios e fornecendo o repositorio
1. Para verificar el estado de los cambios en un repositorio
<code>git status </code>

2. Ver diferencias entre las versiones (commits) de los archivos
<code>git diff </code>

3. Añadir un archivo para ser guardado (commit)
<code>git add <NOMBREDELARCHIVO> </code>

4. Para añadir todos los archivos con cambios
<code>git add . </code>

5. Para crear un commit (guardar) los cambios que añadiste con un mensaje corto que los describe
<code>git commit -m "tu descripción del commit" </code>
