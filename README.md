# wordpress + Mysql

### Descrição.
  - Ambiente: 
    - Portal de conteúdo em Wordpress e banco de dados Mysql em container.
    - O ambiente esta definido em um arquivo docker-compose com as configurações 
  do banco de dados e do wordpress, onde os valores das variáveis como, usuário, 
  password e nome do banco de dados podem ser alterados de acordo com a necessidade, 
  assim como a porta para expor o serviço para a maquina local.

### Como utilizar.
  - Para utilizar é necessário o docker e docker-compose instalados na máquina.
    - Para construir essa aplicação basta executar os seguintes comandos:
    - Dentro do mesmo diretório do arquivo docker-compose.yaml execute:
      `docker-compose up -d`
    - Aguarde até que o processo de download e a criação dos containers esteja concluída.
    - Acesso o browser com o endereço ` <localhost:8080> `
    _ Para encerrar a aplicação, execute o comando:
      `docker-compose down`


  