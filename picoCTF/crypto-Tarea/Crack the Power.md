
Descripcion:
We received an encrypted message. The modulus is built from primes large enough that factoring them isn’t an option, at least not today. See if you can make sense of the numbers and reveal the flag.Download the [message](https://challenge-files.picoctf.net/c_amiable_citadel/f8301c52de77777b21934124245535e3672ea83b3d1976fc984c0affd45dba6f/message.txt).
Solucion(s):
picoCTF{t1ny_e_381870dd}
Notas:
el texto cifrado era una potencia perfecta de 20 (sin desbordamiento modular), por lo que el texto plano es la raíz 20 entera de `c`.
Referencias: