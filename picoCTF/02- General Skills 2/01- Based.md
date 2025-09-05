
Descripcion
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29221`.

Solucion(s):
eduar-picoctf@webshell:~$  nc jupiter.challenges.picoctf.org 29221
Let us see how data is stored
pear
Please give the 01110000 01100101 01100001 01110010 as a word.
...
you have 45 seconds.....

Input:
pear
Please give me the  164 145 163 164 as a word.
Input:
test
Please give me the 6c697a617264 as a word.
Input:
lizard
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_00a975ff}

Notas: conectamos primero al servidor dado con el comando "nc"
se nos asignaron cararcteres para desifrar su contenido. 
todo los cararcteres se pasaron a cyberchef para que los desifrara.

Referencias:
https://gchq.github.io/CyberChef/#recipe=From_Binary('Space',8/disabled)From_Octal('Space'/disabled)From_Hex('None')&input=NmM2OTdhNjE3MjY0&oeol=FF