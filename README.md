# Git-tutorial-basic
Tutorial sobre el uso de Git para Código IoT

El primer cambio realizado en git, permitio acceder  a la carpeta donde se encuentra almacenado el archivo ejecutando el comando:

>nano README.md

Con este comando se nos permitira editar el contenido del archivo desde la terminal.


Con el segundo cambio realizado en git se puede verifiacar el estado de un archivo git ejecutando el comando:

>git status

Este comando nos permitira verificar si hay nuevas versiones sin actualizar del archivo (en caso de haber realizado algun cambio), asi como visualizar las 
versiones anteriores del mismo. Si deseamos actualizar (agregar) los cambios realizados a un archivo en especifico de nuestro repositorio,ejecutamos el comando:

>git add <NombreDelArchivo>.<ExtensionDelArchivo>

Si, en cambio, se desea actualizar todos los cambios realizados, basta con escribir el comando:

>git add .

Utilizando el comando:

>git commit -m "NombreDelCambioRealizado"

Podemos registrar, en el historia de nuestro archivo git, las actualizaciones realizadas. Asegurandonos de guardar los cambios en la rama principal con el
comando 

>git push

Otra forma de editar un archivo es accediendo desde la pagina de: http://github.com donde accederemos al archivo que deseamos editar, en este caso accederemos a README.md y darremos click a la herramienta "Editar este archivo" el cual se encuentra marcado con el simbolo de un lapiz. A l momento de realizar los cambios en el archivo se sugiere realizar un commit de los cambios realizados al archivo, mismo que podremos realizar desde la sección Commit change, misma que aparecera en la parte inferior del archivo en edición

Para actualizar los cambios realizados desde el editor web en la computadora, basta con escribir el comando:

>git pull

Esto se puede demostrar al volver a acceder al archivo git desde nuestra computadora
