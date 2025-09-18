
Descripcion:
This website can be rendered only by **picobrowser**, go and catch the flag! `https://jupiter.challenges.picoctf.org/problem/50522/` ([link](https://jupiter.challenges.picoctf.org/problem/50522/)) or http://jupiter.challenges.picoctf.org:50522.

Solucion(s):
eduar-picoctf@webshell:~$ curl https://jupiter.challenges.picoctf.org/problem/50522/flag -H "User-Agent:picobrowser" | grep pico

 picoCTF{p1c0_s3cr3t_ag3nt_51414fa7}
 
Notas:
Se ultiliza el comando "curl" para hacer una peticion como un navegador diferente.

Referencias:
Observaciones hechas en clase.