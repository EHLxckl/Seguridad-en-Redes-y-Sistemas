

#### Description
There is a nice program that you can talk to by using this command in a shell: `$ nc mercury.picoctf.net 7449`, but it doesn't speak English...

Solucion 1:

eduar-picoctf@webshell:~$ nc mercury.picoctf.net 7449 > arreglo.txt

eduar-picoctf@webshell:~$ perl -pe '$_=join("",map {chr} split)' arreglo.txt

picoCTF{g00d_k1tty!_n1c3_k1tty!_f2d7cafa}

##Notas:
-Se utiliza el comado "nc" en linux para conectar a un puerto de un sitio web.

-El contenido se guarda en un arreglo tipo texto.

-Se utiliza el comando "perl -pe '$_=join("",map {chr} split)'"  de linux para poder combertir los datos de tipo ASCII en caracteres alfanumericos.

##Referencias:
Observaciones hechas en clase.