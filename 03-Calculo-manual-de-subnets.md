Bom o calculo seguite terá como principal foco responder a três perguntas fundamentais:
1-Qual é o tamanho do bloco?
2-Onde começa cada sub-rede?
3-Quais iPs são hosts validos?


####  R: O tamanho do bloco é a quantidade de endereço ip que cada subrede tem
formula: tamanho do bloco = 2^ (bits de host)
Resolução 1 
EX:  ipv4 tem: 32 bits, levando isso em consideração:

 Pegando um endereço ip 192.168.1.0/26 
 tendo essa esse ip sabemos que 26 Bits são usados pra identificar a rede então devo applicar essa informação da seguinte forma
 32bits da rede ipv4 - 26bits usados pra achar a rede = 6 bits de host
 colocando na formula 2^ (bits de host)
                      2 elevado a 6 = 64  ou seja cada subnet tem 64 ips no total incluindo host, network e broadcast

Exemplo visual: 
192.168.1.0
192.168.1.64
192.168.1.128
192.168.1.192  È um exemplo de subnet /26 pula de 64 em 64 

METODO 2: Usando a mascara
Tendo como exemplo a mascara 255.255.255.192
sabendo que o ipv4 tem 32 bits e é dividido em 4 octeto
Fica assim 11111111.11111111.11111111.11000000 
              8    +    8    +    8    +    2  =  26 sendo /26
Como sei qu o ultimo octeto dará 11000000? Olhando uma tabela fixa dos binários segue a tabela:

0......................00000000
128....................10000000
192....................11000000
224....................11100000
240....................11110000
248....................11111000
252....................11111100
254....................11111110
255....................11111111

*então 255.255.255.192 Olhando a tebela de binarios fixos sabemos que 192 equuivale a 11000000*

              
              


