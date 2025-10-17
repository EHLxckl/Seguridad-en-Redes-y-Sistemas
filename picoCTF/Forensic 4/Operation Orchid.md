
Descripcion:
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/212/disk.flag.img.gz)
Solucion(s):
mmls disk.flag.img 
fls disk.flag.img -o 2048
fls disk.flag.img 472 -o 411648
icat -o 411648 disk.flag.img 1875
icat -o 411648 disk.flag.img 1782 > flag.txt.enc
openssl aes256 -d -salt -in flag.txt.enc -out flag.txt -k unbreakablepassword1234567
cat flag.txt  
picoCTF{h4un71ng_p457_0a710765}
Notas:
- descargar el archivo y descomprimir con el comando gunzip.
- aplicar los anteriores comandos.
Referencias:
https://www.youtube.com/watch?v=rXY4BCtonJs