# retrosfera


> By Daniel Martin Corpa

[Readme.md](https://github.com/danicorpa/retrosfera)
# Tabla de contenidos
- [INTRODUCCION](#introduccion)
- [PRIMERA PARTE: TRABAJAR CON FICHEROS MARKDOWN](#primera-parte-trabajar-con-ficheros-markdown)
- [SEGUNDA PARTE: BIFURCAR UN REPOSITORIO](#segunda-parte-bifurcar-un-repositorio)
- [TERCERA PARTE: CÓMO HACER LO MISMO EN GIT BASH (con comandos) Y EN IntelliJ IDEA](#tercera-parte-cómo-hacer-lo-mismo-en-git-bash-con-comandos-y-en-intellij-idea)
# Introducción
Lo retro está volviendo con paso firme. Hace unos años yo llevaba unos pantalones con pata ancha, no de campana, pata ancha, de elefante la llamaban,y ahora vuelvo a verlos en la gente.
Espero que no vuelvan las camisas de chorreras, por Dios!!  :monocle_face:
## PRIMERA PARTE: TRABAJAR CON FICHEROS MARKDOWN
Crea un repositorio con el nombre que te sugiera el propio GitHub, público, con
una descripción, un fichero README.md, un fichero .gitignore (modelo por defecto
para ficheros Java) y licencia MIT.

![](../repositorio_p04/img/crear_repo.png)
Clónalo para tener una copia del repositorio en local.
![](../repositorio_p04/img/clonar_repo.png)
Modifica el README.md de forma que contenga, al menos:
- Encabezados de dos niveles distintos
-  Al menos un enlace
-  Al menos una imagen
-  Al menos un emoji
-  Parte del texto en cursiva
-  Parte del texto en negrita
-  Una lista no numerada
-  Una lista numerada
-  … y lo que tú quieras ponerle

Confirma los cambios en [README.md](https://github.com/danicorpa/retrosfera)
![](../repositorio_p04/img/1er_commit.png)
Sube los cambios que has hecho en local al repositorio en GitHub.
![](../repositorio_p04/img/github_commit.png)
## SEGUNDA PARTE: BIFURCAR UN REPOSITORIO
Busca en GitHub un repositorio que contenga ejercicios de programación en Java.
![](../repositorio_p04/img/fork.png)
Bifúrcalo, para tener una copia del repositorio en tu cuenta de GitHub.
> Pinchando en el botón ![](../repositorio_p04/img/fork3.png)
se bifurca el repositorio
seleccionado y se hace una copia en tu github.
>![](../repositorio_p04/img/fork2.png)

Clónalo (como prefieras: con comandos o con IntelliJ) para poder tener una copia en tu
equipo local.
![](../repositorio_p04/img/clone.png)
Modifica el contenido del repositorio en local. Por ejemplo: cambia el contenido de algún
fichero, añade algún fichero nuevo, elimina algún fichero…
> Creo un archivo y compruebo que se ha añadido en la cola del stagging.
>![](../repositorio_p04/img/git_status.png)

> Lo añado a la cola de seguimiento para que lo tenga en cuenta el próximo commit
que haga.
>![](../repositorio_p04/img/status.png)

Confirma los cambios que has hecho y súbelos al repositorio en GitHub.
>![](../repositorio_p04/img/commit.png)
> Hago el push y el commit para confirmar la subida.

Después de hacer esto, ¿ha cambiado el repositorio que tenías bifurcado en tu cuenta?
>![](../repositorio_p04/img/subido.png)
> Como se aprecia en la imágen se ve el archivo que he creado.

¿Ha cambiado el repositorio a partir del cual has hecho la bifurcación?
>![](../repositorio_p04/img/subido.png)
> El original sigue igual, no ha cambiado.

## TERCERA PARTE: CÓMO HACER LO MISMO EN GIT BASH (con comandos) Y EN IntelliJ IDEA
Para cada uno de los comandos que hemos visto en local, hay una
correspondencia (más fácil) en los menús de IntelliJ IDEA. Así, de paso, repasamos los
comandos y lo que hace cada uno. Muestra con capturas de pantalla si es posible (si no,
escribe la secuencia de pasos a realizar) cómo harías en IntelliJ IDEA lo mismo que los
siguientes comandos:

Git Bash (comandos)        | IntelliJ IDEA        |      
----------------------------|----------------------------
Comprbar el estado del repositorio|
git init|![](../repositorio_p04/img/git_init.png)Menu/Git/Manage remotes...
Comprbar el estado del repositorio|
git status|![](../repositorio_p04/img/git-status.png)Menu/Git/Commit
Añadir ficheros al área de preparación|
git add|![](../repositorio_p04/img/git_init.png)Menu/Selected File/Add
Confirmar cambios|
git commit|![](../repositorio_p04/img/git_commit.png)Menu/Git/Commit
Mostrar el registro de los cambios realizados|
git log|![](../repositorio_p04/img/git_log.png)Menu/Git/Show Git Log
Ver qué repositorios remotos tenemos conectados a nuestro repositorio local|
git git remote -v|![](../repositorio_p04/img/git_init.png)Menu/Git/Manage Remotes
Subir cambios realizados y confirmados al repositorio remoto|
git push|![](../repositorio_p04/img/git_init.png)Menu/Git/Push
Clonar un repositorio remoto a mi equipo local|
git clone|![](../repositorio_p04/img/git-clone.png)Menu/Git/Clone

Entrega: documentación de la práctica en pdf (o .md si te atreves) y enlace a los
repositorios en GitHub. Recuerda en todo caso las normas de entrega.
