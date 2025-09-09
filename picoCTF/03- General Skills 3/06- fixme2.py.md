
Descripcion:
Fix the syntax error in the Python script to print the flag.[Download Python script](https://artifacts.picoctf.net/c/4/fixme2.py)

Solucion(s):
eduar-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/4/fixme2.py

eduar-picoctf@webshell:~$ nano fixme2.py
eduar-picoctf@webshell:~$ python3 fixme2.py
  File "/home/eduar-picoctf/fixme2.py", line 22
    if flag = "":
       ^^^^^^^^^
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
eduar-picoctf@webshell:~$ nano fixme2.py
eduar-picoctf@webshell:~$ python3 fixme2.py
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_e8814d03}

Notas:
se utilizo el comando wget para decargar el archivo.
con el comando nano se pudo editar el codigo del .py y se guardaron los cambios
se utilizo el conmando python3 para ejecutar el archivo .py

Referencias:
https://albertoestrada.es/hacking/editor-de-texto-gnu-nano/