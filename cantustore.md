```markdown
+------------------------+           +------------------------+
|     Cloud Pública      |           |   Infraestrutura Local |
|                        |           |                        |
|   +----------------+   |           |   +----------------+   |
|   | MySQL / Backup |   |           |   |  Active        |   |
|   +----------------+   |           |   |  Directory     |   |
|   |  Backend       |   |           |   |                |   |
|   |  Dotnet 8     |    |           |   |                |   |
|   +----------------+   |           |   |  Firewall      |   |
|   |  Frontend     |    |           |   |  FileServer    |   |
|   |  Node.js      |    |           |   |                |   |
|   +----------------+   |           |   |  Firewall      |   |
|   |  Firewall      |   |           |   |  PrintServer   |   |
|   +----------------+   |           |   +----------------+   |
|                        |           |                        |
+------------------------+           +------------------------+
            |                                  |
            |                                  |
            |                                  |
            +--------------------------+-------+
                                         |
              +--------------------------+---+----------------------+
              | Resiliência de Dados                                |
              | | MySql |                                           |
              | | Backup |                                          | 
              | | Estratégia Disaster Recovery |                    |
              +--------------------------+---+----------------------+
              +--------------------------+---+----------------------+
              | Observabilidade                                     |
              |    | Zabbix |                                       | 
              |    | Grafana |                                      |
              |    | LogDog |                                       | 
              +--------------------------+---+----------------------+
                                         |
                                         |
    +------------------------------------+---+------------------------------------------------+
    | Gestão de Custos Eficiente                                                              |
    | Instâncias reservadas, automações de escalabilidade, revisão periódica de uso de        |   
	| recursos, monitor uso de recursos e custos em tempo real, utilizar a ferramenta própria | 
	| da nuvem "Azure Cost Management".                                                       |
    +-----------------------------------------------------------------------------------------+
```