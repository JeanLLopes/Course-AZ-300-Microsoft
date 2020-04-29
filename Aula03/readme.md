## VIRTUAL NETWORK (VIRTUAL NETWORK)

**VNET**

Criação de redes virtuais onde é possivel criar regras espeficicas, como firewall, liberações de porta, ... Dentro dessas VNET' s é possivel colocar as maquinas virtuais especificas


Quando é criada uma nova rede , no item de seguraça a proteção de DDOS Basica é gratuita, porem é possivel habilitar proteções pagas.

Por padão usar o **BASIC**

Quando vc tem uma maquina virtual é possivel adiciona-la a uma VNET

Em uma maquina Virtual é possivel conectra remotamente na maquina usando o IP publico da maquina que esta disponivel no painel Overwiew

<br>

### ROTEAMENTO DE REDE (NETWORK ROUTING)

Todas as regras de roteamento criados pelo usuario sobrepoe as regras da Microsoft padrão

Network Virtual Appliance (NVA) = São maquinas que gerenciam o roteamento de comunicação entre maquinas dentro da rede do Azure

Network Virtual Appliance funciona como um firewall onde toda solicitaçaõ de rede bate neste NVA para consultar as regras.

**BGP** = usado pra propagação de rota, faz a propagação de novos endereços ser mais rapida, geralmente usado quando ha necessidade de express routing

<br>

### VNET PEERING

-   VNET Peering Regional
    -   usando para conectar duas maquinas da mesma região


-   VNET Peering Global
    -   usando para conectar maquinas que estão em diferentes regiões
    -   não tem peering entre nuvem diferentes
    -   não aceita load balance


<br>




