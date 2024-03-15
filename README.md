# Backbone-MPLS-BGP-VRF
## Projeto de topologia utilizando software Eve-NG.

Nesta página você encontra informações relevantes sobre o projeto e estrutura de organização dos arquivos.

Nesta página: apenas o resumo descritivo principal e notas de versão.
Notas de versão: A cada alteração na topologia independente de que natureza seja a alteração, haverá uma nova pasta nomeada "Version X", contendo um "Readme" descrevendo a topologia e também conterá os arquivos de log, configuração e evidências.


## Notas de versão

```
Version 1.0
* Contem Backbone MPLS de rede de transporte sobre OSPF
* Configuração de 2 redes remotas distantes cada uma com seu ASN e interligadas usando L3VPN
* Protocolos de roteamento OSPF, MPLS, BGP, VRF
```

```
Version 2.0
* Created Bastion Server/Jump Server to access routers on MPLS topology
* Configuration for remote access, telnet and ssh, in Backbone MPLS: access only using the Linux Server
* No encryption and more security added due the limitations in Eve-ng
```

### Informações importantes: 

Devices images

Cisco c7200-adventerprisek9-mz.152-4.S7.image

[Cisco isrv-universalk9.17.03.03](https://labhub.eu.org/UNETLAB%20II/addons/qemu/Cisco%20ISRv/isrv-universalk9.17.03.03.tgz)

[Linux Ubuntu Server](https://labhub.eu.org/UNETLAB%20I/addons/qemu/linux-ubuntu-18.04-server)


### Current Topology



<p float="left"><img src="https://github.com/arthurddduarte86/Backbone-MPLS-BGP-VRF/blob/main/Version%202.0/Screenshot.png"></p>