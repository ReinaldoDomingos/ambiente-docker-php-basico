# Configuração básica para Ambiente docker Apache PHP e MySQL
2 Contêineres Docker com as configurações básicas para desenvolvimento ou execução de aplicação PHP ultilizando servidor Apache e MySQL.

Executar:

    docker-compose up -d

Acesse: http://localhost/ e deve aparecer a mensagem:
Connected to MySQL

Parar container:

    docker-compose stop
    
Na pasta www deve estar os projetos a qual o servidor irá carregar.