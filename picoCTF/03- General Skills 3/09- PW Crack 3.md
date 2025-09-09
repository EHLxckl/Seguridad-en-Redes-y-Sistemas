
Descripcion:
Can you crack the password to get the flag?Download the password checker [here](https://artifacts.picoctf.net/c/16/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/16/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/16/level3.hash.bin) in the same directory too.There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.

Solucion(s):

eduar-picoctf@webshell:~$ python3 level3.py level3.flag.txt.enc
Please enter correct password for flag: 865e
Welcome back... your flag, user:
picoCTF{m45h_fl1ng1ng_2b072a90}

Notas:
Se utilizo elcomando wget para descargar los archivos.
se utulizo el comando nano para observar el codigo del .py
se ejecuto el programa .py pasandole como parametro el otro archivo.
La contrasenia se obtuvo observando el codigo del .py

Referencias:
https://albertoestrada.es/hacking/editor-de-texto-gnu-nano/