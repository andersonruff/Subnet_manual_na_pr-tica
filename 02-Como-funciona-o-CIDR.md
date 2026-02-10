O que é o cidr(Classless Inter-Domain Routing)??? 
O cidr é uma forma de representar redes ip que indica de maneira objetiva quantos BITS  pertencem a rede e quantos pertencem ao host.
Em vez de trabalhar apenas com máscaras fixas (Classes A, B e C), o CIDR permite flexibilidade no tamanho das redes, tornando o uso de endereços IP mais eficiente.

EXEMPLO:  192.168.0.1/24

*****nesse exemplo o endereço base é 192.168.0.1 e o numero de BITS é 24, esse é a quantidadde de bits usado pra identificar a rede.



O QUE SIGNIFICA O NUMERO DEPOIS DA BARRA(/)????

***Ele indica quantos BITS dos 32 bits do ipv4 pertenccem a rede 
IPV4 SEMPRE TEM 32 BITS NO TOTAL

EXMPLO: 32 bits ipv4 é o total;
dele 24 BITS DA REDE E 8 DO HOST

#### 32 - 24 = 8 #### ou seja 8 bits para hosts.
 o cdir é apenas outra forma de descrever a mascara da rede

 CDIR                       MASCARA
 /8                        255.0.0.0
 /16                       255.255.0.0
 /24                       255/255/255/0
 /26                       255/255/255/192
 /30                       255/255/255/252
 
