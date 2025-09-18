
Descripcion:
What was I last working on? I remember writing a note to help me remember...You can download the challenge files here:

- [challenge.zip](https://artifacts.picoctf.net/c_titan/67/challenge.zip)

Solucion(s):
eduar-picoctf@webshell:~$ unzip challenge.zip 
eduar-picoctf@webshell:~$ cd drop-in/
eduar-picoctf@webshell:~/drop-in$ ls
message.txt

eduar-picoctf@webshell:~/drop-in$ cat message.txt 
This is what I was working on, but I'd need to look at my commit history to know why...eduar-picoctf@webshell:~/drop-in$ git log -p

picoCTF{t1m3m@ch1n3_5cde9075}![[gitcommit.png]]



Notas:
Se descarga el archivo usando el comando wget.
Se descomprimio usando unzip.
dentro de la carpeta se utilizo el conmando cat para ver lo que tenia dentro el unico archivo de texto.

Se solisita que obtengamos el hitorial de git, para lo que utilizamos el siguiente comadon (git log -p).

Referencias:
https://primer.picoctf.org/#_git_version_control