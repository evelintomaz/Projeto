# Objetivo e Escopo
*Criar uma empresa com 40 ou mais hosts ativos.*

## Empresa
_DirtyTrash - Industria de Máquinas LTDA_

## Setores

- Engenharia
- Projeto e plano de controle de produção (PCP)
- Comercial
- Compras
- Recursos Humanos
- Financeiro
- Produção
- Reuniões
- Gerência

# Projeto - Rede Lan

## Descrição sumária
*Rede com  45 hosts em dois pisos distintos, separados em subredes para os 7 setores descritos acima.* 

## Tecnologias utilizadas
- *Roteador*
- *Switches*
- *Access Point*


## Diagrama lógico

Tamanho da Estrura


## Diagrama de Topologia

Disposição dos dispositivos na estrutura da empresa

![Preview](assets/mapa3d.png)
[Visualizar em PDF de alta definição](/assets/mapa3d.pdf)

## Diagrama de Cabeamento

Disposição do cabeamento da rede

![Preview](assets/cabeamento.png )
[Visualizar em PDF de alta definição](assets/cabeamento.pdf)


## Definição de cabeamento

![Preview](assets/mapadeconexoes.png)
[Visualizar em PDF de alta definição](/assets/mapadeconexoes.pdf)
[Clique aqui para baixar o projeto do Packet Tracer](assets/rede.pkt)



# Mapa de Conexões

TABELA

# Previsão de Custos

## Definição de Equipamentos
- *Roteador Mikrotik Routerboard 750* - **R$ 339,00**
- *Switch Unifi USW-Pro-24-POE* - **R$ 3.711,69**
- *Access Point UniFi AP HD* - **RS 1.853,19**

## Definição de Materiais
- *Cabeamento Cat.6 Furukawa U/UTP CM/CMR* - **R$ 3.000,00**
- *Soquetes RJ45 de parede* - **R$ 226,56‬**
- *Plugs RJ45* - **R$ 60,00**

## Mão de Obra
- *Hora Técnica*: **R$ 40,00**
- *Instalação*: **R$ 1.300,00**

## Resumo Orçamentário
- *Equipamentos:* **R$ 5.903.88**
- *Materiais:* **R$ 3.286,56**
- *Mão de Obra:* **R$ 1.340,00**
- *Frete e transporte:* **R$ 1.432,68**

- *Custo total:* **RS 11.966,12**

# Configurações da rede
- Os computadores das subredes **Produção 1** e **Produção 2** podem acessar a pasta **Projetos em andamento** na subrede **Engenharia**.
- Os computadores da subrede **Financeiro** podem acessar a subrede **Comercial**
- Os computadores da subrede **Gerência** podem acessar **todas** as subredes.
- Os computadores da subrede **Projetos e Plano de controle de Produção** podem acessar os a pasta **Projetos a serem executados** na subrede **Engenharia**.
- Os computadores das subredes **Financeiro**, **Compras** e **Recursos Humanos** estão limitadas à uma conexão de **20 MBit/s** cada.
- Os computadores das subredes **Engenharia**, **Projeto e plano de controle de produção**, **Produção** e **Gerência** não têm limitações de velocidade.
- Os compuitadores das subredes **Reunião** e **Comercial** estão limitadas à uma conexão de **100 MBit/s**.





