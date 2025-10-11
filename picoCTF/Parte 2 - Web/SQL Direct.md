
Descripcion:
Connect to this PostgreSQL server and find the flag!

Additional details will be available after launching your challenge instance.
Solucion(s):
psql -h saturn.picoctf.net -p 56290 -U postgres pico

picoCTF{L3arN_S0m3_5qL_t0d4Y_31fd14c0}

Notas:
se conecta a una base de datos y realisamos los siguientes comandos.
\list. \c pico. \d flags. 
por ultimo se  realisa la sentencia sql "select * from flags;"
Referencias:
https://www.youtube.com/watch?v=ar34AcZ5I3Y