
Descripcion:
Run the `runme.py` script to get the flag. Download the script with your browser or with `wget` in the webshell.[Download runme.py Python script](https://artifacts.picoctf.net/c/34/runme.py)

Solucion(s):
eduar-picoctf@webshell:~$ wget https://artifacts.picoctf.net/c/34/runme.py

eduar-picoctf@webshell:~$ cat runme.py 
#!/usr/bin/python3
# Python script which just prints the flag

flag ='picoCTF{run_s4n1ty_run}'
print(flag)

Notas:
-Se utilizo wget para decargar el archivo
-Se utilizo el comando cat para buscar la bandera dentro del codigo de python.

Referencias:
https://platzi.com/blog/como-ejecutar-programas-py-en-ubuntu/