# 1. Que es el control de versiones❓

Mecanismo por el cual ***gestionamos cambios*** en archivos o proyectos a lo largo del tiempo, esto nos permite tener un registro de cada modificacion realizada, sabremos quien, cuando lo modifico y porque lo hizo. 

Por ejemplo, si estamos trabajando en un archivo y cometemos un error el ***control de versiones*** nos permitira volver atras y restaurar a una version anterior del archivo, evitando la perdida de trabajo.


# 2. Que es `clone` en GIT❓

El comando `git clone` sirve para copiar un repositorio desde un ***servidor remoto*** a un ***equipo local*** de trabajo. Hace una copia completa del historial y de los archivos del proyecto, para poder trabajar con ellos dE manera local.

- ***Descarga el repositorio:*** Copia todos los archivos, commits y ramas del repositorio remoto.
- ***Crea una copia local:*** Guarda todo en un nuevo directorio en la maquina local.
- ***Conecta con el repositorio original:*** La copia locaL sigue vinculada al repositorio remoto, de manera que podemos descargar actualizaciones o subir nustros propios cambios.


# 3. Cual es el comando para agregar los archivos a la `zona de preparacion`❓

***`git add <archivo.txt>`***
	
- Para agregar un archivo especifico:***`git add archivo.txt`***
- Para agregar todos los archivos modificado en el directorio actual: ***`git add .`***
- Para agregar un conjunto de archivos que coincidadn con un patron: ***`git add *.txt`***


# 4. Cual es el comando para enviar la captura de los archivos modificados a GITHUB❓

Para enviar cambios a GITHUB utilizamos el siguiente comando: ***`git push`***

***`git push`*** es el comando que usamos para enviar nuestros cambios locales a un repositorio remoto.

Sube commits y actualiza la rama de trabajo

Por ejemplo: ***`git push origin <nombre-de-la-rama>`***

🏠 [***Regresar***](./README.md)

