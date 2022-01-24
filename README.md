## ZABBIX ## 

***

*Zabbix* é um software de monitoramento de rede, servidores, serviços e aplicações web.
O intuito desse software é coletar dados em tempo real dos equipamentos e enviar para
uma interface web, onde é possível administrar, monitorar e criar alertas específicos
para cada tipo de item coletado. 
***

Adequado para dois tipos de instalações referente ao software Zabbix

* O primeiro tipo de instalação seria utilizando o arquivo de configuração docker-compose.yml, onde todos os componentes do zabbix vão ser instalados em uma única máquina, inclusive o banco de dados. 

* O segundo tipo de instalação seria utilizando o arquivo de configuração docker-swarm.yml, onde vão ser configurados em forma de serviço e podendo ser replicados entre os workers. 

 *Observação: O arquivo de configuração tem um template de deploy incluso, portanto assim que o serviço é parado ele já inicia automaticamente sem precisar de interação com os containers.* 


~~~~ Ambiente de produção

Em ambientes de produção, não manter as mesmas senhas que o arquivo do repositório.

~~~~
