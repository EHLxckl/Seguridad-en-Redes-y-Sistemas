
Descripcion:
Help us test the form by submiting the username as `test` and password as `test!`

Additional details will be available after launching your challenge instance.
Solucion(s):
url -L -v -d 'username=test&password=test!' http://saturn.picoctf.net:57577/login

 Connection #0 to host saturn.picoctf.net left intact
* Issue another request to this URL: 'http://saturn.picoctf.net:57577/next-page/id=cGljb0NURntwcm94aWVzX2Fs'
* Re-using existing http: connection with host saturn.picoctf.net
> GET /next-page/id=cGljb0NURntwcm94aWVzX2Fs HTTP/1.1
> Host: saturn.picoctf.net:57577
> User-Agent: curl/8.15.0
> Accept: */*

</head>
<body>
    <script>
        setTimeout(function () {
           // after 2 seconds
           window.location = "/next-page/id=bF90aGVfd2F5X2JlNzE2ZDhlfQ==";
        }, 0.5)
      </script>
    <p></p>
* Connection #0 to host saturn.picoctf.net left intact
</body>   

echo 'cGljb0NURntwcm94aWVzX2FsbF90aGVfd2F5X2JlNzE2ZDhlfQ==' | base64 -d

picoCTF{proxies_all_the_way_be716d8e} 
Notas:
se hace una peticion con el comando 'curl' 
pedimos el username y el password .
copeamos lo que nos arroga en la parte de id=

se descodifica en base64
Referencias:
https://www.youtube.com/watch?v=WKQ5dajA2fQ