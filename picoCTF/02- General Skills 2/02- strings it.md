
Descripcion:
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/94d00153b0057d37da225ee79a846c62/strings) without running it?

Solucion(s):
wget https://jupiter.challenges.picoctf.org/static/94
d00153b0057d37da225ee79a846c62/strings

eduar-picoctf@webshell:~$ ls 
README.txt  arreglo.txt  file  flag  strings  todo
eduar-picoctf@webshell:~$ strings strings | grep "picoCTF"
picoCTF{5tRIng5_1T_d66c7bb7}

Notas:
decargamos con el comando "wget"
y con el comando "string" sacamos el contenido filtrado 
pasandole lo que queremos buscar.

Referencias:
https://linux.die.net/man/1/strings