## GIT

Paso 1 - Inicializar y conectar:
- git init -> Inicializar git en un proyecto
- git remote add origin <enlace-repo> -> Contectar el proyecto con un repositorio

Paso 2 - Registrar cambios
- git status -> Revisar que cambios estan sin registrar
- git add <archivo> -> Registrar archivo
- git add . -> Registrar todos los archivos

Paso 3 - Crear backups (commits)
- git commit -m "nombre de commit" -> Commit veloz, solo pide titulo.
- git commit -> Abre cajon, permite colocar descripcion. Se guarda al cerrar el cajon.
- git log -> Permite ver la lista de commits realizados. El que tenga el HEAD es el ultimo realizado.
- git checkout "id commit" -> Me muevo a la version del commit correspondiente al ID ingresado.

Paso 4 - Pushear cambios de PC al repo
- git push origin <nombre-rama-remota> -> Envia cambios a la rama principal o rama remota
- git push -> Enviar cambios a rama paralela

Pas 5 - Descargar cambios pusheados de Repo a PC
- git pull -> Trae los cambios de la rama en la que estamos parados de repo a PC.

Paso 6 - Crear una rama paralela
- git branch <nombre-rama> -> Crea una rama
- git checkout <nombre-rama> -> Movernos a la rama <nombre-rama>
- git checkout -b <nombre-rama> -> Crear una rama y movernos automaticamente a ella.

Paso 7 - Fusiones
- git merge <nombre-rama-a-fusionar> -> Tiramos este comando parados en la rama que quiere
recibir la fusion, y fusionamos <nombre-rama-a-fusionar> con la rama en la que estamos parados.