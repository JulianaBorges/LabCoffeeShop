COMANDOS PARA EXECUÇÃO DO SISTEMA:

acesse a pasta pelo terminal com o comando:

$cd POO_PHP

após execute:

$docker-compose up

---------------------------------------------

acesso do banco de dados

servidor:
user: root
senha: root

---------------------------------------------
caso de erro para conectar o banco de dados execute: 

$docker-compose exec php docker-php-ext-install pdo pdo_mysql mysqli

após a instalação restart o doker:

$docker-compose stop
$docker-compose start
----------------------------------------------

não der um kill no container, user stop quando finalizar o desenvolvimento