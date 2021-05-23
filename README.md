# aprovisiona_zabbix_agent2_linux
Playbook para aprovisionamento do agente do Zabbix para hosts Linux distribuição Centos

# Funcionamento
Realiza o download e instalação do agente do zabbix a partir do repositório oficial </br>
Utiliza facts e algumas variavéis estáticas para funcionamento </br>
Realiza upload do arquivo /etc/zabbix/zabbix_agent2.conf customizado via facts para target </br>

# Utilização
Preencher as variáveis no arquivo /vars/main.yml de acordo com a necessidade.
