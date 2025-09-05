

Descripcion:
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm) has extraordinarily helpful information...

Solucion(s):
wget https://mercury.picoctf.net/static/f95b1ee9f29d631d99073e34703a2826/warm.

eduar-picoctf@webshell:~$ ls
README.txt  arreglo.txt  file  flag  strings  todo  warm
eduar-picoctf@webshell:~$ ./warm

eduar-picoctf@webshell:~$ chmod +x warm

eduar-picoctf@webshell:~$ ./warm --help
I don't know what '--help' means! I do know what -h means though!
eduar-picoctf@webshell:~$ ./warm -h    
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_f0668f62}

Notas:
-Descarga el archivo con el comando wget 
-Cambiamos los permisos para el archivo descargado con "chmod +x 'archivo'"
-Ejecutamos el programa descargado con "./'arcghivo' -h"
-la opcion "-h" nos ayuda a saberque hace el binario.

Referencias:
Observaciones hechas en clase.