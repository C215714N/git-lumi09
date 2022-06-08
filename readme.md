# GIT Desarrollo Colaborativo

Esta guia fue realizada con el objetivo de facilitar el uso y comprension de la herramienta GIT, la cual se utiliza para el control del versionado de nuestros proyectos.

## Configuracion Inicial

Cuando inicializamos un repositorio debemos hacerlo en la carpeta del proyecto que queremos gestionar, en caso que necesitemos definir un nombre de usuario y correo para las confirmaciones podemos utilizar el parametro *--global* para indicarle a git que guarde dicha configuracion en la carpeta del usuario y de esta manera, estara disponible para todos los proyectos.

* **git init**: Inicializa un repositorio de git.
* **git config *--global* user.name `username`**: Define el nombre de usuario con el que nos identificamos.
* **git config *--global* user.email `email`**: Establece el correo de contacto para las confirmaciones.