
Descripcion:
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/12/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/12/level1.flag.txt.enc) in the same directory too.

Solucion(s):
eduar-picoctf@webshell:~$ nano level1.py
eduar-picoctf@webshell:~$ python3 level1.py level1.flag.txt.enc 

Please enter correct password for flag: 8713
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_1b2fd683}

Notas:
Se utilizo elcomando wget para descargar los archivos.
se utulizo el comando nano para observar el codigo del .py
se ejecuto el programa .py pasandole como parametro el otro archivo.
La contrasenia se obtuvo observando el codigo del .py

Referencias:
https://albertoestrada.es/hacking/editor-de-texto-gnu-nano/