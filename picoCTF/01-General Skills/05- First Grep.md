
#### Description

Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file)? This would be really tedious to look through manually, something tells me there is a better way.

Solucion 1:
eduar-picoctf@webshell:~$ wget https://jupiter.challenges.picoctf.org/static/515f19f3612bfd97cd3f0c0ba32bd864/file

eduar-picoctf@webshell:~$ egrep 'picoCTF' file

picoCTF{grep_is_good_to_find_things_5af9d829}

##Notas:
-Primero se introduce el comando de linux para obtener un archivo de un citio web.
-Segundo se utiliza el comando "egrep"
de linux para poder buscar en un archivo la palabra.

##Referencias
https://ryanstutorials.net/linuxtutorial/grep.php