# retrosfera


> By Daniel Martin Corpa

[Readme.md](https://github.com/danicorpa/retrosfera)
# Tabla de contenidos
- [INTRODUCCION](#introduccion)
- [PRIMERA PARTE: TRABAJAR CON FICHEROS MARKDOWN](#primera-parte-trabajar-con-ficheros-markdown)
- [SEGUNDA PARTE: BIFURCAR UN REPOSITORIO](#segunda-parte-bifurcar-un-repositorio)
- [TERCERA PARTE: CÓMO HACER LO MISMO EN GIT BASH (con comandos) Y EN IntelliJ IDEA](#tercera-parte-cómo-hacer-lo-mismo-en-git-bash-con-comandos-y-en-intellij-idea)
# Introducción
Lo retro está volviendo con paso firme. Hace unos años yo llevaba unos pantalones con pata ancha, no de campana, pata ancha, de elefante la llamaban, y ahora vuelvo a verlos en la gente.
Espero que no vuelvan las camisas de chorreras, por Dios!!  :monocle_face:
Volviendo al tema, lo retro está volviendo, en el mundo de la informática, que es lo que nos toca por donde estamos metidos.
Recuerdo como con mis 12 o 13 años, yo me iba con mis amigos a un sitio turbio, lleno de mala gente y de miradas furtivas, un sitio al que llamabamos RECREATIVOS!!. Ese sitio repleto de máquinas recreativas que, por cinco duros, veinticinco pesetas, te llevaba a mundos míticos, estadios de fútbol, canchas de baloncesto, peleas con moinstruos,  buf, se me calienta la boca!!
En fin, por cinco duros pasabas un rato de diversión que podía ir desde unos segundsos a horas de juego.
Pero de lo que vamos a hablar aquí es de un ordenador mítico que me enamoró en mi más tierna infancia, nada más y nada menos unos 12 años, y me brindó horas de disfrute y aprendizaje que forjó en mí un especial gusto por está tecnología.

## PRIMEROS PASOS
Rondaba el año del Señor de 1989, aprox, y mi madre no aguantó mi llantina pidiendole que me comprara un ordenador, que iba a hacer unos trbajos para el cole chchis, que iba a aprender muchas con las aplicaciones que llevaba incorporadas, pobre infeliz, y lo iba a petar.
Entonces un día, mi amada madre vino con uno debajo del brazo, nada menos que un amstrad, ![](../retrosfera/img/libro.jpg), si, en esa época venía con instrucciones!!:heart_eyes:. 

Nadie me advirtio que el soporte de datos que usaba era UNA CINTA MAGNÉTICA!!, una maldita cinta magnética, ese momento de carga era entre una pesadilla y un momento de emoción. Hasta que la carga fallaba después de media hora cargando!! Otra vez a cargar!!
Menos mal que mi madre me compró el que llevaba diskete, :blush: y eso me llevaba a ir al corte inglés a comprarme mis amados disketes para hacer mis copias de seguridad de los juegos que más me gustaban, ahí fue cuando encontré el segundamano, si si, el segundamano, un periódico de venta de objetos de segunda mano, como wallapop pero en los 80!!:innocent:
era la caña.
En fin, me tiras de la lengua y me voy por las ramas, por donde iba, a sí, mi amstrad nuevecito, ese ordenador de 8bits, 128kb de RAM, 48kb de ROM, madre mía la de cosas que se podía hacer con esos recuros, ![](../retrosfera/img/juego_batman.jpg)

![](../repositorio_p04/img/crear_repo.png)
Clónalo para tener una copia del repositorio en local. incorporadas
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
