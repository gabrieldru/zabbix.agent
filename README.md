![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.jpg)

1º O Script tem como função dar interatividade na instalação do Zabbix Agent em ambientes Windows.\
2º Oferecer opções de remoção total, upgrade e downgrade de versão de forma simples e interativa.\
3º Fornece ao Administrador um padrão unificado de instalação do Zabbix Agent, facilitando upgrades/downgrades.

Desenvolvido por Diego Cavalcante\
Script: agent.zabbix.ps1\
Versão: 1.9\
Linguagem: Powershell\
E-Mail: diego@suportecavalcante.com.br\
Skype: suportecavalcante\
Download: [Baixar via AWS](https://s3-sa-east-1.amazonaws.com/suportecavalcante.com.br/downloads/zabbix/agent.zabbix.zip)

Para informações de uso, verifique o arquivo LEIA-ME.txt

Criação = Versão 1.0 29/08/2017 (Script Básico de instalação do Zabbix Agent).\
Update  = Versão 1.1 30/08/2017 (ADD Campo "Pasta de Instalação", ADD Selecionar Porta, ADD Liberar Firewall).\
Update  = Versão 1.2 31/08/2017 (ADD Opção REMOVE Agent Full e cria um backup da pasta original com a data atual).\
Update  = Versão 1.3 31/08/2017 (ADD Opção de selecionar a versão de instalação).\
Update  = Versão 1.4 01/09/2017 (ADD Teste de conectividade na porta 10051 do Server/Proxy).\
Update  = Versão 1.5 02/09/2017 (ADD Opção CHANGE para Upgrade/Downgrade de versão do Zabbix Agent).\
Update  = Versão 1.6 05/09/2017 (ADD INSTALL Opção que verifica se a versão escolhida existe no instalador).\
Update  = Versão 1.7 08/12/2017 (ADD Variável que substitui no zabbix_agentd.conf tudo que foi digitado interativamente).\
Update  = Versão 1.8 09/12/2017 (ADD CHANGE Opção que verifica se a versão escolhida existe no instalador).\
Update  = Versão 1.9 11/12/2017 (Contribuição Mário Alves - ADD parâmetros para instalação via rede).

# INSTALL
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.install01.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.install02.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.install03.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.install04.png)

# REMOVE
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.remove01.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.remove02.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.remove03.png)

# UPGRADE/DOWNGRADE
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.change01.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.change02.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.change03.png)
![alt tag](https://github.com/suportecavalcante/zabbix.agent/blob/master/screenshots/zabbix.agent.change04.png)
