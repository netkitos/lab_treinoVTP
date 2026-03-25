## Projeto: Implementação de Rede com VLAN, Trunking e VTP
Simulação de uma rede de um prédio administrativo de 3 andares utilizando a hierarquia Core e Access.

### Tecnologias Utilizadas
Cisco Packet Tracer

Protocolo VTP (VLAN Trunking Protocol)

IEEE 802.1Q (Trunking)

VLANs para segmentação de departamentos (TI, RH, Comercial)

### Desafios Superados
Durante a implementação, identifiquei um problema de sincronização no 1º andar (SW_Comercial). O switch não recebia o domínio VTP automaticamente. A sincronização completa da topologia foi validada após a criação das VLANs no Switch Core, o que incrementou o Revision Number e forçou a atualização dos switches em modo Client através dos links de Trunking.
