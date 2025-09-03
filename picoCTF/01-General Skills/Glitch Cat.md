

#### Description

Our flag printing service has started glitching!

Additional details will be available after launching your challenge instance.?

Our flag printing service has started glitching!`$ nc saturn.picoctf.net 53234`

Solucion 1:

eduar-picoctf@webshell:~$ nc saturn.picoctf.net 53234
'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'

eduar-picoctf@webshell:~$ python 
Python 3.10.12 (main, Feb  4 2025, 14:57:36) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
KeyboardInterrupt
>>> 
KeyboardInterrupt
>>> python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'python' is not defined
>>> picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}
  File "<stdin>", line 1
    picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}
           ^
SyntaxError: invalid syntax
>>> 
KeyboardInterrupt
>>> 'picoCTF{gl17ch_m3_n07_' + chr(0x39) + chr(0x63) + chr(0x34) + chr(0x32) + chr(0x61) + chr(0x34) + chr(0x35) + chr(0x64) + '}'
'picoCTF{gl17ch_m3_n07_9c42a45d}'

##Notas

##Referencias