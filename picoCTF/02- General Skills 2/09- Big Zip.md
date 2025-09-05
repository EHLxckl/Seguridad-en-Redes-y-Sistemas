
Descripcion:
Unzip this archive and find the flag.

- [Download zip file](https://artifacts.picoctf.net/c/503/big-zip-files.zip)

Solucion(s):

wget https://artifacts.picoctf.net/c/503/big-zip-files.zip

unzip  big-zip-files 

cd big-zip-files/

grep -r "picoCTF"

picoCTF{gr3p_15_m4g1c_ef8790dc}

Notas:
decargamos el archivo y descomprimimos.
con el comando "grep" buscamos la bandera.

Referencias:
tutorial de uso del grep.