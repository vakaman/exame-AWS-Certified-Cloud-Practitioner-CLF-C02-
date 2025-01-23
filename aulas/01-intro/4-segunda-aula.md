## O que é cloud computing?


### Antes

* Antes de se tornar comum a disponibilização de serviços em núvem era muito comum que as empresas tivessem toda a complexidade dos serviços em sua infraestrutura
* Servidores de diversos tipos eram mantidos em salas 
* Essas salas precisavam de refrigeração, devido a quantidade de máquinas ativas. 
* Um consumo de energia considerável era esperado devido a todas as necessidades envolvendo a estrutura.
* Complexo e dificil de manter
* Custo elevado quando o assunto é manter a escala vertical.


### Depois

* Datacenters ao redor do mundo acabaram nascendo
* Podemos escolher qual o mais proximo utilizar, e não precisamos nos preocupar com o recover em caso de falha.
* Custos com energia, refrigeração, link e atualização de servidores, acabam sendo cobrados em forma de serviço
* Fácil de escalar
* Ampla gama de serviços 
* Alta disponibilidade


---

### Vantagens

* Baixo custo
* Flexibilidade
* Escala global
* Agilidade

--- 

### Tipos de cloud

* IAAS -> ( Infraestructure as a service ) 
    * Locação de infraestrutura 
        * Servidores
        * VM
        * Storage
    * Estes recursos são focados em locação de recurso computacional, e não envolvem configuração,
    * Basicamente é a tercerização de recursos de hadware.
* PAAS ( Plataform as a service )
    * Locação de recursos de plataforma
        * Banco de dados
        * Hospedagem de sites 
        * Máquina já com S.O
* SAAS ( Software as a service)
    * Locação de licença de uso de aplicação
        * Email
        * Dropbox 
        * Drive


## Implementações

### Nuvem pública

Recursos de hardware compartilhado. Imagine um cluster de servidores onde diversos clientes consomer o recurso sob demanda ou com limite específicado. 
A cloud se responsabiliza pela segurança e garante que um cliente não irá ter acesso aos recursos dos outros clientes, mesmo compartilhando o mesmo hardware. 

* Aws
* Azure
* GCP

### Nuvem privada

Recurso de hardware dedicado, mesmo estando em nuvem é possível contratar um serviço onde o recurso do hardware é 100% dedicado, normalmente grandes instituições utilizam este tipo de abordagem.

* Bancos
* Governos
* Financeiras

### Nuvem hibrida

Parte dos recursos podem fazer parte de um hardware compartilhado e parte pública. 

