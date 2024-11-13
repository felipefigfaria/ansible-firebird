Implementado roles, separando por atividades: atualização de pacotes dos sistemas operacionais, criação de diretório /DATABASE e a instalação do Firebird propriamente dita. Feito também diferenciação de distribuição Linux dentro de cada task.

Arquivo hosts também foi aprimorado, separando os targets por grupos (UBUNTU e ROCKY) e incluindo esses grupos em um grupo principal (LINUX).

Sendo utilizado autenticação por chaves SSH.

E feita configuração do arquivo ansible.cfg, setando algumas configurações como caminho padrão para o arquivo hosts e roles.