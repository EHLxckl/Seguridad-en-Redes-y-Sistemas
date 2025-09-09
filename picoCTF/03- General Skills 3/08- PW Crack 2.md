
Descripcion:
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/13/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/13/level2.flag.txt.enc) in the same directory too.

Solucion(s):
eduar-picoctf@webshell:~$ nano level2.py
eduar-picoctf@webshell:~$ python3 level2.py level2.flag.txt.enc 

Please enter correct password for flag: de76

picoCTF{tr45h_51ng1ng_489dea9a}

Notas:
Se utilizo elcomando wget para descargar los archivos.
se utulizo el comando nano para observar el codigo del .py
se ejecuto el programa .py pasandole como parametro el otro archivo.
La contrasenia se obtuvo observando el codigo del .py

Referencias:
https://albertoestrada.es/hacking/editor-de-texto-gnu-nano/