
Descripcion:
Why search for the flag when I can make a bookmarklet to print it for me?

Additional details will be available after launching your challenge instance.

Solucion(s):
http://titan.picoctf.net:51424/

picoCTF{p@g3_turn3r_18d2fa20}

        javascript:(function() {
            var encryptedFlag = "àÒÆÞ¦È¬ëÙ£ÖÓÚåÛÑ¢ÕÓ¨ÍÕÄ¦í";
            var key = "picoctf";
            var decryptedFlag = "";
            for (var i = 0; i < encryptedFlag.length; i++) {
                decryptedFlag += String.fromCharCode((encryptedFlag.charCodeAt(i) - key.charCodeAt(i % key.length) + 256) % 256);
            }
            alert(decryptedFlag);
        })();
    
Notas:
solo se agrega el link a la parte del navegador llamado bookmark.
En bookmark se edita el URL y se pone el codigo que aparece en la paguina.
en bookmark selecioneas el link agregado y te dala flag.
Referencias:
video youtube.