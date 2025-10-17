
Descripcion:
Use `srch_strings` from the sleuthkit and some terminal-fu to find a flag in this disk image: [dds1-alpine.flag.img.gz](https://mercury.picoctf.net/static/920731987787c93839776ce457d5ecd6/dds1-alpine.flag.img.gz)
Solucion(s):
picoCTF{f0r3ns1c4t0r_n30phyt3_564ff1a0}
Notas:
- descargamos el archivo y utilizamo el comando gunzip para descomprimir.
- luego usamos el comando 'srch_strings nombre_archivo | grep pico' para optener la bandera.
Referencias:
https://www.youtube.com/watch?v=8vGqrtl87JI