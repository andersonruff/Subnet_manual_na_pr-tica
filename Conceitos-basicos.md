 NETWORK ADDRESS (192.168.1.0)
Representa a identificação da rede.
Não pode ser atribuída a um dispositivo.
O que isso significa na prática?? 
*Ex: Imagine da seguinte forma, o NETWORK ADDRESS é o cep da rua e não o numero da casa.
Ele NÃO pode ser: celular, pc, servidor, impressora, câmera(iot) etc..
Conclusão: O Network Address não “fica” em nenhum dispositivo.
Ele existe na lógica da rede, não fisicamente.
Onde ele é usado? Regras de bloqueio/liberação (firewall), rotas em roteadores(roteamento), 
identificação de VPC(cloud), definição de rede remota(VPN). etc..

BROADCAST  (192.168.1.255)
Endereço usado para comunicação com todos os hosts da rede.
Ele é o responsavel por mandar mensagem pra todos os dispositivos da rede.
Ex: Ele é como um alto falante gritando pra todo mundo.
Onde ele é usado? DHCP pra oferecer ip de forma automática a dispositivos ma rede, descoberta de redes, impressora, pc etc..

 First Host (192.168.1.1)
Primeiro IP válido para dispositivos, normalmente usado como gateway.
Ele representa o primeiro endereço válido pra dispositivos.
Uso comum em modem, roteador, firewall, por ser fácil de lembrar, organização da rede etc..
más não é obrigatório ser nesses dispositivos.

 Last Host (192.168.1.254)
Último IP válido para dispositivos.
Muito usado em equipamentos fixos, servidores, facil de lembrar e também por questão de organização

 Total de Hosts
Em uma rede /24 temos:
2⁸ - 2 = 254 hosts válidos
