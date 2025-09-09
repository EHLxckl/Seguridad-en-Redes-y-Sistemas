
Descripcion:
Run the Python script `code.py` in the same directory as `codebook.txt`.

- [Download code.py](https://artifacts.picoctf.net/c/3/code.py)
- [Download codebook.txt](https://artifacts.picoctf.net/c/3/codebook.txt)

Solucion(s):

eduar-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/3/codebook.txt
eduar-picoctf@webshell:~$ python3 code.py codebook.txt
picoCTF{c0d3b00k_455157_197a982c}

Notas:
se utilizo el comando wget para descargar el archivo .py
con el cmando python3 ejecutamos el archivo .py 
en la misma ejecucion sele pasa un archivo para que lo compile junto.

Referencias:
https://platzi.com/blog/como-ejecutar-programas-py-en-ubuntu/