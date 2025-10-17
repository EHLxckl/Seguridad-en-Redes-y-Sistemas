
Descripcion:
Our server seems to be leaking pieces of a secret flag in its logs. The parts are scattered and sometimes repeated. Can you reconstruct the original flag?Download the [logs](https://challenge-files.picoctf.net/c_saffron_estate/1a0b2a2a67149850cd0e6d34da005c381bbbed4c558e529fec8b3be3f8619046/server.log) and figure out 
the full flag from the fragments.

Solucion(s):
grep -r "picoCTF" server.log
grep -r "FLAGPART" server.log
picoCTF{us3_y0urlinux_sk1lls_cedfa5fb}
Notas:
comando grep para ver que se encuentra en el archivo.
Referencias: