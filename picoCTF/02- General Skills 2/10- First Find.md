
Descripcion:
Unzip this archive and find the file named 'uber-secret.txt'

- [Download zip file](https://artifacts.picoctf.net/c/500/files.zip)
Solucion(s):
wget https://artifacts.picoctf.net/c/500/files.zip

unzip files.zip 

 cd files/ 

 grep -r "picoCTF" .

picoCTF{f1nd_15_f457_ab443fd1}

Notas:
decargamos el archivo y descomprimimos.
con el comando "grep" buscamos la bandera.

Referencias:
Tutorial de uso de "grep"