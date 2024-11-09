___
## Introdução

O socket é uma biblioteca em python que serve para mexermos com redes e fazer 
diferentes requisições:

___
## Comandos

`socket.scoket()` = serve para criar um objeto que vai servir como forma de 
comunicação de rede, sendo TCP ou UDP, usando ipv4 ou ipv6.

`AF_INET` = endereços ipv4
`AF_INET6` = endereços ivp6

`SOCK_STREAM` = comunicação TCP
`SOCK_DGRAM` = comunicação UDP

___
## Coisas que você pode fazer com o objeto socket:

`.connect()` = para se conectar em um servidor e portas específicos
`.send()` para enviar dados a um servidor já conectado
`.recv()` = para receber dados de um servidor conectado
`.close()` = fechar conexão com o servidor

`.sendto("host, port")` = para comunicação UDP
`.recvfrom()` = para receber a resposta enviada

`variavel_string.encode("utf-8")` = para fazer a conversão em bytes de forma que o
servidor entenda.

`resposta_string.decode("utf-8")` = para decodificar uma string binaria

___
