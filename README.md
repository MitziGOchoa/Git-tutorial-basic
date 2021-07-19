# Git-tutorial-basic
Primer acercamiento a Git. Tutorial sobre el uso de Git para Código IoT


#### Acceso y edicion de un archivo en un repositorio Git

Para acceder  a la carpeta donde se encuentra almacenado el archivo a editar por medio de git, se ejecuta el comando:

>nano "NombreDelArchivo".md

Con el que se editara el contenido del archivo desde la terminal.

#### Estado de un repositorio Git y actualización de versiones

Para verifiacar el estado de repositori git se ejecuta el comando:

>git status

El cual nos permitira verificar si hay nuevas versiones sin actualizar del archivo modificado(en caso de haber realizado algun cambio), asi como visualizar las 
versiones anteriores del mismo. Si deseamos actualizar (agregar) los cambios realizados a un archivo en especifico de nuestro repositorio,ejecutamos el comando:

>git add "NombreDelArchivo"."ExtensionDelArchivo"

Si, en cambio, se desea actualizar todos los cambios realizados, basta con escribir el comando:

>git add .

#### Historial de modificaciones. Comando commit

Utilizando el comando:

>git commit -m "NombreDelCambioRealizado"

Podemos comentar en el historia de nuestro archivo git, las actualizaciones realizadas. Asegurandonos de guardar los cambios en la rama principal con el
comando 

>git push

#### Edición desde el visor grafico de git

Otra forma de editar un archivo es accediendo desde la pagina de: http://github.com donde accederemos al archivo que deseamos editar, dando click a la herramienta "Editar este archivo" el cual se encuentra marcado con el simbolo de un lapiz. Al momento de realizar los cambios en el archivo, se sugiere realizar un commit de los mismos. Esto lo podremos realizar desde la sección Commit change, la cual parecera en la parte inferior del archivo en edición

Para actualizar los cambios realizados desde el editor web en la computadora, basta con escribir el comando:

>git pull

Esto se puede comprobar al volver a acceder al archivo git desde nuestra computadora
