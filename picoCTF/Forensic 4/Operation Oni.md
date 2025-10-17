
Descripcion:
Download this disk image, find the key and log into the remote machine.Note: if you are using the webshell, download and extract the disk image into `/tmp` not your home directory.

Additional details will be available after launching your challenge instance.
Solucion(s):
file disk.img  
mmls disk.img  
fls disk.img -o 206848 
fls -o 206848 disk.img 470
fls -o 206848 disk.img 3916
icat -o 206848 disk.img 2345 
icat -o 206848 disk.img 2346
icat -o 206848 disk.img 2345 > id_ed25519
chmod 600 id_ed25519 
ssh -i id_ed25519 -p 62571 ctf-player@saturn.picoctf.net
picoCTF{k3y_5l3u7h_b5066e83}
Notas:
- descargar el archiivo y descomprimir con el comando gunzip.
- serguir los pasos anteriores.
Referencias:
https://www.youtube.com/watch?v=HSAciVN6Jq8