# Objetivo e Escopo
*Criar uma empresa com 40 ou mais hosts ativos.*

## Empresa
_DirtyTrash - Industria de Máquinas para tratamento de lixo e reciclagem LTDA_

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
- Almoxarifado

# Projeto - Rede Lan

## Descrição sumária
*Rede com  45 hosts em dois pisos distintos, separados em subredes para os 10 setores descritos acima. 

- *A área da empresa (galpões e escritório) é de aproximadamente 10.400m³*.

## Tecnologias utilizadas
- *Roteador*
- *Switches*
- *Access Point*
- *Cabeamento Categoria 6*


## Diagrama lógico

A rede é conectada num link de 500 MBit/s (Download) por 250 MBit/s (Upload) fornecida pelo provedor Vivo, no modelo Fibra óptica. A central de conexões é no andar superior, numa sala dedicada para isso, com temperatura controlada. Esta sala foi escolhida pois está numa posição vantajosa (quase centralizada). O cabeamento do andar inferior converge para a sala do setor **Engenharia**, e então é encaminhado por meio de um eletroduto para a sala do servidor. O cabeamento totaliza 836m nos mais de 10,400m³ da empresa.


## Diagrama de Topologia

Disposição dos dispositivos na estrutura da empresa

A empresa possui dois galpões de 44m de profundidade, por 16,9m de largura. A parte que centraliza os escritórios possuem 3,5m por andar, totalizando 7m dos dois andares. 

*A área da empresa (galpões e escritório) é de aproximadamente 10.400m³*.

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

| Setor                | Equipamento  | Porta | Descrição                  | Status  | Identificação do Cabo | Endereço IP   | Gateway       | Metragem |
|----------------------|--------------|-------|----------------------------|---------|-----------------------|---------------|---------------|----------|
| Almoxarifado         | Switch-01    |    17 | Alm-1                      | Em uso  | VRD-15                | 192.168.10.20 | 192.168.10.6  | 24m      |
| Almoxarifado         | Switch-01    |    19 | Alm-2                      | Em uso  | VRD-17                | 192.168.10.21 | 192.168.10.6  | 25m      |
| Almoxarifado         | Switch-01    |    15 | Impressora-5               | Em uso  | VRD-13                | 192.168.10.47 | 192.168.10.6  | 26m      |
| Controle de Produção | Switch-01    |     7 | PCP-1                      | Em uso  | VRD-5                 | 192.168.10.32 | 192.168.10.9  | 22m      |
| Controle de Produção | Switch-01    |     9 | PCP-2                      | Em uso  | VRD-7                 | 192.168.10.33 | 192.168.10.9  | 26m      |
| Controle de Produção | Switch-01    |    11 | PCP-3                      | Em uso  | VRD-9                 | 192.168.10.34 | 192.168.10.9  | 27m      |
| Controle de Produção | Switch-01    |    13 | PCP-4                      | Em uso  | VRD-11                | 192.168.10.35 | 192.168.10.9  | 29m      |
| Controle de Produção | Switch-01    |     5 | Impressora-4               | Em uso  | VRD-3                 | 192.168.10.46 | 192.168.10.9  | 23m      |
| Engenharia           | Switch-01    |     8 | Eng-1                      | Em uso  | VRD-6                 | 192.168.10.22 | 192.168.10.7  | 12m      |
| Engenharia           | Switch-01    |    10 | Eng-2                      | Em uso  | VRD-8                 | 192.168.10.23 | 192.168.10.7  | 13m      |
| Engenharia           | Switch-01    |    12 | Eng-3                      | Em uso  | VRD-10                | 192.168.10.24 | 192.168.10.7  | 14m      |
| Engenharia           | Switch-01    |    14 | Eng-4                      | Em uso  | VRD-12                | 192.168.10.25 | 192.168.10.7  | 15m      |
| Engenharia           | Switch-01    |    16 | Eng-5                      | Em uso  | VRD-14                | 192.168.10.26 | 192.168.10.7  | 17m      |
| Engenharia           | Switch-01    |    18 | Eng-6                      | Em uso  | VRD-16                | 192.168.10.27 | 192.168.10.7  | 21m      |
| Engenharia           | Switch-01    |    20 | Eng-7                      | Em uso  | VRD-18                | 192.168.10.28 | 192.168.10.7  | 26m      |
| Engenharia           | Switch-01    |    22 | Eng-8                      | Em uso  | VRD-20                | 192.168.10.29 | 192.168.10.7  | 24m      |
| Engenharia           | Switch-01    |    24 | Eng-9                      | Em uso  | VRD-22                | 192.168.10.30 | 192.168.10.7  | 21m      |
| Engenharia           | Switch-01    |     4 | Impressora-8               | Em uso  | VRD-2                 | 192.168.10.50 | 192.168.10.7  | 25m      |
| Engenharia           | Switch-01    |     6 | Impressora-9               | Em uso  | VRD-4                 | 192.168.10.51 | 192.168.10.7  | 23m      |
| Produção 1           | Switch-01    |    23 | PRD1-1                     | Em uso  | VRD-21                | 192.168.10.41 | 192.168.10.8  |  65m     |
| Produção 1           | Switch-01    |    21 | Impressora-6               | Em uso  | VRD-19                | 192.168.10.48 | 192.168.10.8  | 66m      |
| Produção 2           | Switch-01    |     3 | PRD2-1                     | Em uso  | VRD-1                 | 192.168.10.31 | 192.168.10.8  | 51m      |
| Roteador             | Switch-01    |     1 | Rot-1 (Roteador Principal) | Em uso  | BLU-1                 | 192.168.10.1  | 192.168.10.1  | 0,5m     |
| Sala do Servidor     | Switch-01    |     2 | ---- Daisy Chain ----      | Em uso  | ORG-1                 | 192.168.10.15 | 192.168.10.1  | 0,5m     |
| Comercial            | Switch-02    |    18 | Com-4                      | Em uso  | VRM-17                | 192.168.10.10 | 192.168.10.5  | 15m      |
| Comercial            | Switch-02    |    20 | Com-5                      | Em uso  | VRM-19                | 192.168.10.11 | 192.168.10.5  | 17m      |
| Comercial            | Switch-02    |    22 | Com-6                      | Em uso  | VRM-21                | 192.168.10.12 | 192.168.10.5  | 19m      |
| Comercial            | Switch-02    |    12 | Com-1                      | Em uso  | VRM-11                | 192.168.10.7  | 192.168.10.5  | 16m      |
| Comercial            | Switch-02    |    14 | Com-2                      | Em uso  | VRM-13                | 192.168.10.8  | 192.168.10.5  | 18m      |
| Comercial            | Switch-02    |    16 | Com-3                      | Em uso  | VRM-15                | 192.168.10.9  | 192.168.10.5  | 20m      |
| Comercial            | Switch-02    |    10 | Impressora-7               | Em uso  | VRM-9                 | 192.168.10.49 | 192.168.10.5  | 22m      |
| Compras              | Switch-02    |    19 | Cps-1                      | Em uso  | VRM-18                | 192.168.10.42 | 192.168.10.4  | 7m       |
| Compras              | Switch-02    |    21 | Cps-2                      | Em uso  | VRM-20                | 192.168.10.43 | 192.168.10.4  | 5m       |
| Compras              | Switch-02    |    17 | Impressora-3               | Em uso  | VRM-16                | 192.168.10.17 | 192.168.10.4  | 4m       |
| Financeiro           | Switch-02    |    11 | Fin-1                      | Em uso  | VRM-10                | 192.168.10.4  | 192.168.10.3  | 15m      |
| Financeiro           | Switch-02    |    13 | Fin-2                      | Em uso  | VRM-12                | 192.168.10.5  | 192.168.10.3  | 14m      |
| Financeiro           | Switch-02    |    15 | Fin-3                      | Em uso  | VRM-14                | 192.168.10.6  | 192.168.10.3  | 17m      |
| Financeiro           | Switch-02    |     9 | Impressora-2               | Em uso  | VRM-8                 | 192.168.10.45 | 192.168.10.3  | 16m      |
| Gerência 1           | Switch-02    |    24 | Ger-1                      | Em uso  | VRM-23                | 192.168.10.13 | 192.168.10.11 | 13m      |
| Gerência 2           | Switch-02    |     3 | Ger-2                      | Em uso  | VRM-2                 | 192.168.10.40 | 192.168.10.11 | 16m      |
| Gerência 2           | Switch-02    |     1 | Impressora-1               | Em uso  | VRM-1                 | 192.168.10.15 | 192.168.10.11 | 17m      |
| Recursos Humanos     | Switch-02    |     5 | RH-1                       | Em uso  | VRM-4                 | 192.168.10.2  | 192.168.10.2  | 10m      |
| Recursos Humanos     | Switch-02    |     7 | RH-2                       | Em uso  | VRM-6                 | 192.168.10.3  | 192.168.10.2  | 14m      |
| Reunião              | Switch-02    |     4 | Reu-1                      | Standby | VRM-3                 | 192.168.10.36 | 192.168.10.10 | 7m       |
| Reunião              | Switch-02    |     6 | Reu-2                      | Standby | VRM-5                 | 192.168.10.37 | 192.168.10.10 | 8m       |
| Reunião              | Switch-02    |     8 | Reu-3                      | Standby | VRM-7                 | 192.168.10.38 | 192.168.10.10 | 9m       |
| Sala do Servidor     | Switch-02    |     2 | ---- Daisy Chain ----      | Em Uso  | ORG-1                 | -------       | 192.168.10.1  | 0,5m     |
| Wi-Fi Recepção       | Switch-02    |    23 | Wi-fi Recepção             | Em uso  | VRM-22                | DHCP          | 192.168.10.1  | 3m       |
| Visitante            | Access Point |       | Celular Visitante          | Em uso  | Wireless              | DHCP          | 192.168.10.1  | Wireless |

[Clique aqui para acessar a tabela no google sheets](https://docs.google.com/spreadsheets/d/1PRmMV3pk3BwJKg33jsCa5jhA2bA7ni3uTRbqm3yuvJI/edit?usp=sharing)


# Previsão de Custos

## Definição de Equipamentos
- *Roteador Mikrotik Routerboard 750* - **R$ 339,00** - [Visualizar Modelo](https://mikrotik.com/product/RB750Gr3)
- *Switch Unifi USW-Pro-24-POE* (R$ 3.711,69) x2 - **R$ 7.423,38** - [Visualizar Modelo](https://store.ui.com/collections/unifi-network-routing-switching/products/usw-pro-24-poe) - [Tecnologia](https://unifi-network.ui.com/switching)
- *Access Point UniFi AP HD* - **RS 1.853,19** - [Visualizar Modelo](https://store.ui.com/collections/unifi-network-access-points/products/unifi-hd)

*Cotação do dólar no dia:* **R$ 5,29**

## Definição de Materiais
- *Cabeamento Cat.6 Furukawa U/UTP CM/CMR* (caixa com 305m) (R$ 3.000,00) x3 - **R$ 9.000,00** - [Visualizar Modelo](https://www.furukawalatam.com/pt-br/catalogo-de-produtos-detalhes/gigalan-cat6-uutp-cmcmr)
- *Soquetes RJ45 de parede* (R$ 4,72/ un) x48 - **R$ 226,56‬** - [Visualizar Modelo](https://pt.aliexpress.com/i/32848621014.html)
- *Plugs RJ45* (pacote c/ 100un) x2 - **R$ 60,00** - [Visualizar Modelo](https://www.submarino.com.br/produto/649763299/kit-pacote-100-unidades-conector-rj45-cabo-rede-lan-plug?pfm_carac=kit%20conector%20rj45%20cat6%20100%20unidades&pfm_page=search&pfm_pos=grid&pfm_type=search_page)

## Mão de Obra
- *Hora Técnica* (R$ 40,00) x16h - **R$ 640,00**
- *Instalação* - **R$ 1.300,00**

## Resumo Orçamentário
- *Equipamentos:* **R$ 9.615.57**
- *Materiais:* **R$ 9.346,56**
- *Mão de Obra:* **R$ 1.940,00**
- *Frete e transporte:* **R$ 1.432,68**


- *Custo total:* **RS 22.334,13**

# Configurações da rede
- Os computadores das subredes **Produção 1** e **Produção 2** podem acessar a pasta **Projetos em andamento** na subrede **Engenharia**.
- Os computadores da subrede **Financeiro** podem acessar a subrede **Comercial**
- Os computadores da subrede **Gerência** podem acessar **todas** as subredes.
- Os computadores da subrede **Projetos e Plano de controle de Produção** podem acessar os a pasta **Projetos a serem executados** na subrede **Engenharia**.
- Os computadores das subredes **Financeiro**, **Compras** e **Recursos Humanos** estão limitadas à uma conexão de **20 MBit/s** cada.
- Os computadores das subredes **Engenharia**, **Projeto e plano de controle de produção**, **Produção** e **Gerência** não têm limitações de velocidade.
- Os compuitadores das subredes **Reunião** e **Comercial** estão limitadas à uma conexão de **100 MBit/s**.

[Clique aqui para acessar a documentação da rede](assets/documentacao.md)


# Equipe

Evelin Tomaz

João Vitor De Souza



