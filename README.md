### Arquitetura Redes (Networks Architecture)
> Ano lectivo de 2013 / 2014 - Universidade de Aveiro

# Objetivo
Executar o desenho técnico, configurar e testar uma rede de telecomunicações de uma empresa de média/grande dimensão.


###1. Tarefas (1a fase)
* Desenho da arquitetura de rede e mapeamento físico da mesma.
* Definição das características/capacidades dos equipamentos de rede.
* Definição da subdivisão de redes ao nível 2 do modelo OSI (VLAN).
* Definição do endereçamento IPv4 e IPV6.
* Planeamento temporal para a execução do projeto [diagrama de Gantt].
* Extras (ex: orçamento, equipamentos não rede, etc...).

###2. Tarefas (2a fase)
* Configuração da camada de acesso e definição da interligação/endereçamento dos equipamentos..
* Configuração das redes locais virtuais (VLAN) e trunks.
* Configuração do encaminhamento unicast IPv4.
* Configuração do encaminhamento unicast IPv6.
* Implementação de mecanismos de tradução de endereços privados. Assumindo que ambos os acessos à Internet estão ativos e existe a possibilidade de encaminhamento assimétrico na Internet.
* Configuração do(s) servidor(es) DNS/DNSSEC da empresa.
* Configuração de mecanismos de transição IPv6/IPv4. Assumindo que é necessário garantir a conectividade IPv6 total entre os polos em caso de falha completa do ISP PT1.
* Configuração das ligações seguras entre polos (e respetivo encaminhamento).
* Implementação de políticas de QoS.
* Script de monitorização (linguagens: bash, python, perl, javascript, java, etc...) para deteção da localização (porta/switch) de um terminal com base no seu endereço MAC.

###2. Tarefas Extra (2a fase)
* Assumindo que nas instalações da empresa existem 2 canais de IPTV para difusão interna, configure o serviço de difusão IP multicast incluindo o encaminhamento multicast IPv4 e IPv6. Configure os mecanismos de encaminhamento multicast de modo a permitir a difusão dos 2 canais a todas as televisões terminais com capacidade de reprodução.
* Configuração de um servidor DHCPv4.
* Configuração de um servidor VPN.
* Configuração de uma ou mais firewalls.
* Sistema de monitorização mais evoluído [com medição da carga nas ligações, alarmes em caso de falha de um interface/link, deteção de ataques de spoofing, etc...].
* Configuração de um servidor DHCPv6.

