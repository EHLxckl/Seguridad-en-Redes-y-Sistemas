
Descripcion:
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: [Addadshashanammu.zip](https://mercury.picoctf.net/static/659efd595171e4c40378be6a2e9b7298/Addadshashanammu.zip)

Solucion(s):
eduar-picoctf@webshell:~$wget https://mercury.picoctf.net/static/659efd595171e4c40378be6a2e9b7298/Addadshashanammu.zip
eduar-picoctf@webshell:~$unzip Addadshashanammu
eduar-picoctf@webshell:~$ ls
Addadshashanammu  Addadshashanammu.zip  README.txt  arreglo.txt  file  flag  ltdis.sh  static  static.ltdis.strings.txt  static.ltdis.x86_64.txt  strings  todo  warm
eduar-picoctf@webshell:~$ cd Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/
eduar-picoctf@webshell:~/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku$ ls
fang-of-haynekhtnamet
eduar-picoctf@webshell:~/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku$ ./fang-of-haynekhtnamet 
*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_524e3dc4}

Notas:
descargamos con el camando "wget"
realizamos un "unzip" para sarcar lo comprimido
utilizamos "ls" para visualizar su contenido
usamos la tecla (Tab) para autocompletar 
"./" para ejecutar el contenido.

Referencias:
Observaciones hechas en clase.