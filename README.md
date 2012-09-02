#Instalação de dependências

### Instalar o composer
	curl -s https://getcomposer.org/installer | php
### Executar

	php composer.phar install

### Configurar Banco de dados
	Alterar as configurações de conexão no bootstrap.php
	Criar a base de dados
### Executar
	./bin/doctrine orm:schema-tool:create
	
	