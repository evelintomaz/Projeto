# Documentação de Rede
# #DirtyTrash - Indústria de máquinas para tratamento de lixo e reciclagem LTDA.

A rede é conectada num link de 500 MBit/s (Download) por 250 MBit/s (Upload) fornecida pelo provedor Vivo, no modelo Fibra óptica. A central de conexões é no andar superior, numa sala dedicada para isso, com temperatura controlada. Esta sala foi escolhida pois está numa posição vantajosa (quase centralizada). O cabeamento do andar inferior converge para a sala do setor **Engenharia**, e então é encaminhado por meio de um eletroduto para a sala do servidor.

# Configurações da rede
- Os computadores das subredes **Produção 1** e **Produção 2** podem acessar a pasta **Projetos em andamento** na subrede **Engenharia**.
- Os computadores da subrede **Financeiro** podem acessar a subrede **Comercial**
- Os computadores da subrede **Gerência** podem acessar **todas** as subredes.
- Os computadores da subrede **Projetos e Plano de controle de Produção** podem acessar os a pasta **Projetos a serem executados** na subrede **Engenharia**.
- Os computadores das subredes **Financeiro**, **Compras** e **Recursos Humanos** estão limitadas à uma conexão de **20 MBit/s** cada.
- Os computadores das subredes **Engenharia**, **Projeto e plano de controle de produção**, **Produção** e **Gerência** não têm limitações de velocidade.
- Os compuitadores das subredes **Reunião** e **Comercial** estão limitadas à uma conexão de **100 MBit/s**

# Subredes

Abaixo está disponível a tabela de configuração de subredes

| Setor                                         | Equipamento | Subrede       |
|-----------------------------------------------|-------------|---------------|
| Engenharia                                    | Switch-01   | 192.168.10.7  |
| Projeto e plano de controle de produção (PCP) | Switch-01   | 192.168.10.9  |
| Comercial                                     | Switch-02   | 192.168.10.5  |
| Compras                                       | Switch-02   | 192.168.10.4  |
| Recursos Humanos                              | Switch-02   | 192.168.10.2  |
| Financeiro                                    | Switch-02   | 192.168.10.3  |
| Produção                                      | Switch-01   | 192.168.10.8  |
| Reuniões                                      | Switch-02   | 192.168.10.10 |
| Gerência                                      | Switch-02   | 192.168.10.11 |
| Almoxarifado                                  | Switch-01   | 192.168.10.6  |

# Rede Wireless

A rede wireless foi configurada para atribuir IPs automaticamente via DHCP.

*SSID:* **WIFI Recepção**

*Senha:* **VISITANTES1!** (WPA-PSK2)

A rede wireless não irá conectar em nenhuma subrede, pois não deverá receber nenhuma permissão de acesso.