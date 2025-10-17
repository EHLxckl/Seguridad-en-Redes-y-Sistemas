
Descripcion:
Hi, intrepid investigator! 📄🔍 You've stumbled upon a peculiar PDF filled with what seems like nothing more than garbled nonsense. But beware! Not everything is as it appears. Amidst the chaos lies a hidden treasure—an elusive flag waiting to be uncovered.Find the PDF file here [Hidden Confidential Document](https://challenge-files.picoctf.net/c_saffron_estate/8175871c08fc4d10d26d10746f3a4aad06bbd7a5682c01c3d777a89d276bdb38/confidential.pdf) and uncover the flag within the metadata.

Solucion(s):
cGljb0NURntwdXp6bDNkX20zdGFkYXRhX2YwdW5kIV9lZTQ1NDk1MH0=
picoCTF{puzzl3d_m3tadata_f0und!_ee454950}
Notas:
se instalo poppler-utils  para leer archivos .pdf en linux.
con el comando pdfinfo "nombre.pdf" obtenemos la informacion del archivo.
la bandera estaba en el nombre del autor en base64.
se utilizo cyberchef para la transformacion.
Referencias:
https://gchq.github.io/CyberChef/#recipe=From_Base64('A-Za-z0-9%2B/%3D',true,false)&input=Y0dsamIwTlVSbnR3ZFhwNmJETmtYMjB6ZEdGa1lYUmhYMll3ZFc1a0lWOWxaVFExTkRrMU1IMD0NCg&ieol=CRLF