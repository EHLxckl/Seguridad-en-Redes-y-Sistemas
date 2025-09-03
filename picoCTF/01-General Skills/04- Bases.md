

#### Description

What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.

Solucion 1:
codigo en python:

import base64

cadena_base64 = "bDNhcm5fdGgzX3IwcDM1"

decodificado_bytes = base64.b64decode(cadena_base64)

decodificado_texto = decodificado_bytes.decode("utf-8")

print(f"La cadena '{cadena_base64}' en Base64 se decodifica como: '{decodificado_texto}'")

La cadena 'bDNhcm5fdGgzX3IwcDM1' en Base64 se decodifica como: 'l3arn_th3_r0p35'


Solucion 2:
codigo en python

import base64
base64.b64decode("bDNhcm5fdGgzX3IwcDM1").decode()
'l3arn_th3_r0p35'

##Notas:
Con la importacion de la biblioteca de python "base64" se pude convertir una cadena de caracteres.

##Referencias:
Observaciones hechas en clase.