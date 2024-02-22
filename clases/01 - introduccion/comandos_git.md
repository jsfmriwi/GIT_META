<!-- el .md es para crear documentación (markdow) -->

comandos para configurar git por primera vez:
-git config --global user.name "your name"
-git config --global user.email "your email"

comando para ver que usuario o que correo está configurado
-git config --global user.name "your name"
-git config --global user.email "your email"
-git config --list

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
ELIMINAR CUENTA Y CONFIGURACION  
rm ~/.gitconfig win
rm ~/.config/git/config ubuntu
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

comando para inicializar git en un repositorio
-git init

comando para mirar el estado de los archivos
-git status

pasos para crear una versión del código

1. agregar los cambios
   -git add _.js (agrega todos los archivos del tipo con el _)
   -git add homa.html (agregar un archivo en especifico)

2. comprometer los archivos
   -git commit -m "Descripción del commit"

!qa cerrar commit

:qa cerrar commit

comando para mostrar todas las versiones hasta el momento

-git log
-git log --oneline (el --oneline muestra solo una linea de código, lo más importante)

comando para devolverse a una versión según la id del commit
-git checkout (nombre rama o commit al que se quiere devolver)
-git checkout 0000000

comando para volver a la ultima version segura
-git checkout main or master

comando para ir a la versión anterior
-git checkout-- . (atajo)
