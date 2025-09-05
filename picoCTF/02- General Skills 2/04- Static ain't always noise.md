
Descripcion:
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/static)? This [BASH script](https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/ltdis.sh) might help!

Solucion(s):
eduar-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/static
eduar-picoctf@webshell:~$ wget https://mercury.picoctf.net/static/ec4dbd8898ade34e1d60d5b70c1b8c8c/ltdis.sh

eduar-picoctf@webshell:~$ ls
README.txt   file  ltdis.sh  static.ltdis.strings.txt  strings  warm
arreglo.txt  flag  static    static.ltdis.x86_64.txt   todo

eduar-picoctf@webshell:~$ cat static.ltdis.strings.txt | grep "pico"
   picoCTF{d15a5m_t34s3r_98d35619}
   
Notas:
decargamos los dos archivos con el comando "wget"
uno de ellos tiene la terminacion ".sh" se ejecuto con el
comando "bash" pasandole el otro archivo y nos resulto un archivo .txt
-con el comando "cat y grep" sacamos  la vandera.

Referencias:
Observaciones hechas en clase.