

#### Description

Our flag printing service has started glitching!

Additional details will be available after launching your challenge instance.?

Our flag printing service has started glitching!`$ nc saturn.picoctf.net 53234`

Solucion 1:

eduar-picoctf@webshell:~$ nc saturn.picoctf.net 53234
'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'

eduar-picoctf@webshell:~$ python 
>>> 'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'
'picoCTF{gl17ch_m3_n07_9c42a45d}'

##Notas:
Se utiliza el comado "nc" en linux para conectar a un puerto de un sitio web.
Despues utilizamos python para pasarle los datos en hexadecimal y hacer la conversion mediante la funcion chr.

##Referencias:
Observaciones hechas en clase.s