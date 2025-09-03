

#### Description

Can you convert the number 42 (base 10) to binary (base 2)?

Solucion 1:
paguina:
def decimal_a_binario(numero):
    if numero == 0:
        return "0"
    
    binario = ""
    while numero > 0:
        residuo = numero % 2
        binario = str(residuo) + binario
        numero = numero // 2
    return binario

##Notas:
Se creo una funcion en python para clacular de base 10 a base 2.

##Referencias
Observaciones hechas en clase.