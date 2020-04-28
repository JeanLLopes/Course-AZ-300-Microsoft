**AZURE MONITOR**


- Consegue metrificar e monitorar subidas de VM' s

- Dá informações de perfomance de VM's sistema operacional e Serverless

- Intervalos de 1min

- Diagnostic Logic
    - Feature que deve ser ligada

- Activy logs
    - Feature que deve ser ligada 

<br>

**AZURE ADVISOR**

Alem de personlizar as VM's é aqui que você recebe as notificações de problemas com as maquinas, porem não resolve nenhum problema apenas é notificado.

Efetua a possibilidade de otimização de custos, dentro das VM's do Azure.

<br>

**AZURE MONITOR ALERTS**

Com os alertas alem de alertar o administrador é possivel executar scripts quando um alerta for acionado, como por exemplo reiniciar a maquina (action group)

Possui intergração via API do Azure, onde você pode integrar com seu sistema chamdos internos

Alem dos alertas por sms, tambem é possivel fazer ligações e integrações via API 

<br>

**OVERVIEW OF ACTIVITY LOG**

Para um caso de DR (desastre recovery) é possivel criarmos uma solução de ASR ( **Azure Site Recovery** _(Ele vai copiar sua maquina byte a byte para ou rede)_)

- **ASR - Azure Site Recovery**
    -   ASR leva apenas VM
    -   Não leva regras de rede como firewall, IP,... 
    -   Outra Vnet e outra Subnet (REDE)

-   **Estudar sobre** : [Vmware Site Recovery](https://www.google.com/search?q=Vmware+Site+Recovery&oq=Vmware+Site+Recovery&aqs=chrome..69i57j0l7.294j0j7&sourceid=chrome&ie=UTF-8)

<br>

**QUERY THE ACTIVITY LOG**

<br>

**ACTIVITY LOG AND LOG ANALYTICS**

É possivel corelacinar informações de log desde que as aplicações usem o mesmo **Azure AD Tenant**, (caso queira pegas informações de diferentes Azure AD Tenants use a solução - **AZURE LOG ANALYTICS DATA COLLECTOR**)) .

manualmente você pode acessar os logs de deletar as atividades de logs usando querys.

<br>

**AZURE LOG ANALYTICS DATA COLLECTOR**

caso você queria corelacionar os logs de diferentes aplicações e de diferentes **Azure AD Tenant**

Como é um recurso Serveless vc paga por execução

<br>

**AZURE STORAGE ACCOUNTS**

o Azure stora accounts possui as seguintes "tiers", cada uma dela com umtipo de performance e preço, quando mais "quente" mais caro e mais rapido

- **HOT** - dado acessado constantemente
- **COOL** - acessado as vezes
- **ARCHIVE** - muito pouco acessado

Não é possivel fazer um upgrade de discos standard para premiun, somente é possivel criar um novo disco com essas configurações

Você paga por GB, por mais eque esteja oculpando apenas alguns megas

<br>

**AZURE IMPORT**

Faz movimentações da sua maquina local para o Azure ou quando voce esta migrando informações de um servidor onpremisse para a Azure

_Quando as informações saem da região você paga ( rede edentro do Azure )_

[mais informações](https://docs.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10)

<br>

**AZCOPY ( Azure Copy )**

Faz a copia de arquivos entre storages da Azure

_Quando as informações saem da região você paga ( rede edentro do Azure )_

<br>

