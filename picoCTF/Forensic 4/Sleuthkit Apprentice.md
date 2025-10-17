
Descripcion:
Download this disk image and find the flag.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

- [Download compressed disk image](https://artifacts.picoctf.net/c/136/disk.flag.img.gz)
Solucion(s):
- icat -f ext4 -o 360448 disk.flag.img 2082
- icat -f ext4 -o 360448 disk.flag.img 2371
- picoCTF{by73_5urf3r_3497ae6b}
Notas:
- usamos icat para obtener datos del archivo en ext4.
Referencias:
https://www.youtube.com/watch?v=1sFEUl8UpM0