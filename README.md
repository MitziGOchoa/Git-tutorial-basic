# Git-tutorial-basic
Tutorial sobre el uso de Git para Código IoT

El primer cambio realizado en git, permitio acceder  a la carpeta donde se encuentra 
almacenado el archivo ejecutando el comando:

>nano README.md

Con este comando se nos permitira editar el contenido del archivo desde la
terminal.

Con el segundo cambio realizado en git se puede verifiacar el estado de un archivo
git ejecutando el comando:

>git status

Este comando nos permitira verificar si hay nuevas versiones sin actualizar del
archivo (en caso de haber realizado algun cambio), asi como visualizar las 
versiones anteriores del mismo

Si deseamos actualizar (agregar) los cambios realizados en nuestro repositorio,
ejecutamos el comando:

>git add <NombreDelArchivo>.<ExtensionDelArchivo>

Utilizando el comando:

>git commit -m "NombreDelCambioRealizado"

Podemos registrar, en el historia de nuestro archivo git, las actualizaciones
realizadas. Asegurandonos de guardar los cambios en la rama principal con el
comando 

>git push
