![GitHub Logo](/Images/unamba.png)
# UNAMBA - EAPIIS 
* 20182
    * curso de ATI
    	* SUBIENDO A GIThub
    
    [GITHUB](https://github.com/20182-ATI/caja-client.git)
unamba
> repositorio ATI
> :shipit: dixroby ac .:smile: ![GitHub Logo](/Images/eapiis.jpg)
> unamba - Apurimac

# Comandos b�sicos de GIT
### git config
Uno de los comandos m�s usados en git es git config, que puede ser usado para establecer una configuraci�n espec�fica de usuario, como ser�a el caso del email, un algoritmo preferido para diff, nombre de usuario y tipo de formato, etc� Por ejemplo, el siguiente comando se usa para establecer un email:
>git config --global user.email sam@google.com

### git init
Este comando se usa para crear un nuevo repertorio GIT:
> *git init*

### git add
Este comando puede ser usado para agregar archivos al index. Por ejemplo, el siguiente comando agrega un nombre de archivo temp.txt en el directorio local del index:
> *git add temp.txt*

### git clone
Este comando se usa con el prop�sito de revisar repertorios. Si el repertorio est� en un servidor remoto se tiene que usar el siguiente comando:
>git clone alex@93.188.160.58:/path/to/repository
Pero si est�s por crear una copia local funcional del repertorio, usa el comando:
>git clone /path/to/repository

### git commit
El comando commit es usado para cambiar a la cabecera. Ten en cuenta que cualquier cambio comprometido no afectara al repertorio remoto. Usa el comando:
>git commit �m �Message to go with the commit here�

### git status
Este comando muestra la lista de los archivos que se han cambiado junto con los archivos que est�n por ser a�adidos o comprometidos.
>git status

### git push
Este es uno de los comandos m�s b�sicos. Un simple push env�a los cambios que se han hecho en la rama principal de los repertorios remotos que est�n asociados con el directorio que est� trabajando. Por ejemplo:
>git push  origin master

### git checkout
El comando checkout se puede usar para crear ramas o cambiar entre ellas. Por ejemplo, el siguiente comando crea una nueva y se cambia a ella:
>command git checkout -b <banch-name>
Para cambiar de una rama a otra solo usa:
>git checkout <branch-name>

### git remote
El comando git se usa para conectar a un repositorio remoto. El siguiente comando muestra los repositorios remotos que est�n configurados actualmente:
>git remote -v
Este comando te permite conectar al usuario con el repositorio local a un servidor remoto:
>git remote add origin <93.188.160.58>

### git branch
Este comando se usa para listar, crear o borrar ramas. Para listar todas las ramas se usa:
>git branch
para borrar la rama:
git branch -d <branch-name>

### git pull
Para poder fusionar todos los cambios que se han hecho en el repositorio local trabajando, el comando que se usa es:
>git pull

### git merge
Este comando se usa para fusionar una rama con otra rama activa:
>git merge <branch-name>

### git diff
Este comando se usa para hacer una lista de conflictos. Para poder ver conflictos con el archivo base usa:
>git diff --base <file-name>
El siguiente comando se usa para ver los conflictos que hay entre ramas que est�n por ser fusionadas para poder fusionarlas sin problemas:
>git diff <source-branch> <target-branch>
Para solo ver una lista de todos los conflictos presentes usa:
git diff

### git tag
Etiquetar se usa para marcar commits espec�ficos con asas simples. Por ejemplo:
>git tag 1.1.0 <instert-commitID-here>

### git log
Ejecutar este comando muestra una lista de commits en una rama junto con todos los detalles. Por ejemplo:
>commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Alex Hunter <alexh@gmail.com>
Date:   Mon Oct 1 12:56:29 2016 -0600

### git reset
Para resetear el index y el directorio que est� trabajando al �ltimo estado comprometido se usa este comando:
git reset - -hard HEAD

### git rm
Este comando se puede usar para remover archivos del index y del directorio que est� trabajando:
>git rm filename.txt

### git stash
Este es uno de los comandos menos conocidos, pero ayuda a salvar cambios que no est�n por ser comprometidos inmediatamente, pero temporalmente:
git stash

### git show
Se usa para mostrar informaci�n sobre cualquier objeto git. Por ejemplo:
>git show

### git fetch
Este comando le permite al usuario buscar todos los objetos de un repositorio remoto que actualmente no reside en el directorio local que est� trabajando. Por ejemplo:
>git fetch origin

### git ls-tree
Para ver un objeto de �rbol junto con el nombre y modo de cada uno de ellos, y el valor blob�s SHA-1, se usa:
>git ls-tree HEAD

### git cat-file
Usando el valor SHA-1, se puede ver el tipo de objeto usando este comando. Por ejemplo:
>git cat-file �p d670460b4b4aece5915caf5c68d12f560a9fe3e4
git grep
Este comando le permite al usuario buscar en los �rboles de contenido cualquier frase o palabra. Por ejemplo, para buscar por www.tupaginaweb.com en todos los archivos se usar�a:
git grep �www.tupaginaweb.com�

### gitk
Este es la interfaz gr�fica para un repositorio local que puede invocar escribiendo y ejecutando:
>gitk

### git instaweb
Con este comando un servidor web puede correr interconectado con el repositorio local. Un navegador web tambi�n est� autom�ticamente dirigido a el:
>git instaweb �http=webrick

### git gc
Para optimizar el repositorio por medio de una recolecci�n de basura, que limpiara archivos innecesarios y los optimizara, usa:
>git hc

### git archive
Este comando le permite al usuario crear archivos zip o tar que contengan los constituyentes de un solo �rbol de repositorio:
>git archive � -format=tar master

### git prune
Con este comando los objetos que no tengan ning�n puntero entrante ser�n eliminados:
>git prune

### git fsck
Para poder hacer un chequeo de integridad del sistema de archivos git, usa este comando. Cualquier objeto corrompido ser� detectado:
>git fsck

### git rebase
Este comando se usa para la re aplicaci�n de los compromisos en otra rama. Por ejemplo:
>git rebase master

> :shipit: atte :dixroby ac .:smile: ![GitHub Logo](/Images/log.gif)