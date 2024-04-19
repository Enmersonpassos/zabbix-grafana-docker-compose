# zabbix-grafana-docker

Implante facilmente um servidor de monitoramento em tempo real usando Zabbix e Grafana. Monitore redes, servidores e serviços com eficiência e visualize dados em dashboards interativos.

Este projeto oferece uma solução simplificada para implantar um servidor de monitoramento usando Zabbix e Grafana. O Zabbix é uma plataforma de monitoramento de código aberto amplamente utilizada para monitorar a integridade e o desempenho de redes, servidores e serviços de rede. Grafana é uma ferramenta de visualização de código aberto que permite criar, explorar e compartilhar dashboards interativos e painéis de controle em tempo real. Combinados, esses serviços oferecem uma solução robusta e escalável para monitorar e visualizar dados em tempo real de uma grande empresa. Este projeto fornece uma configuração automatizada usando Docker e Docker Compose para simplificar o processo de implantação e configuração desses serviços.

Configuração de Servidor para Zabbix e Grafana

Este projeto fornece uma configuração automatizada para implantar um servidor de monitoramento usando Zabbix e Grafana. Com este ambiente, você pode monitorar sistemas e visualizar dados em tempo real de uma grande empresa.
Pré-requisitos

    Docker instalado na máquina local
    Conhecimento básico do Docker e suas funcionalidades
    Este README pressupõe que você está usando um sistema operacional baseado em Unix, como Linux ou macOS.

Como Usar

    Clone este repositório em sua máquina local:

bash

git clone https://github.com/Enmersonpassos/zabbix-grafana-docker.git

cd nome-do-repositorio

    Certifique-se de que o Docker está em execução em sua máquina.

    Execute o seguinte comando para iniciar os serviços do Zabbix e Grafana:

bash

docker-compose up -d

    Após a execução do comando acima, os serviços do Zabbix e Grafana devem estar disponíveis nos seguintes endereços:

    Zabbix: http://localhost:8080
    Grafana: http://localhost:3000

    Faça login nos painéis de administração usando as credenciais padrão:

    Zabbix: Usuário Admin e senha zabbix
    Grafana: Usuário admin e senha admin

    Após o login, você pode começar a configurar e monitorar seus sistemas conforme necessário.

Estrutura do Projeto

    docker-compose.yml: Arquivo de configuração do Docker Compose para definir e iniciar os serviços do Zabbix e Grafana.
    zabbix: Pasta contendo arquivos de configuração específicos do Zabbix.
    grafana: Pasta contendo arquivos de configuração específicos do Grafana.

Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests com melhorias, correções de bugs ou novos recursos que você gostaria de adicionar.
Licença

Este projeto está licenciado sob a MIT License.


