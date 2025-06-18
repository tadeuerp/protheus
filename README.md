Com a intenção de facilitar o desenvolvimento de objetos de negócios e também de resgatar
	informações dos objetos de negócios padrão do Protheus eu desenvolvi uma rotina que busca todos
	os objetos de negócios padrão e customizados do repositório do Protheus.
	
	Essa rotina permite você:
	
	- Salvar o esquema do objeto de negócio.
	- Gerar a linha de comando CURL do objeto de negócio e poder por exemplo importar esse comando
	  para o POSTMAN.
	- Executar o objeto de negócio informando os parametros caso o objeto de negócio use as perguntas
	  da SX1. Caso não use o SX1 nesse primeiro momento eu gero os parametros em branco que apos
      exportar deve ser preenchido manualmente.
	
	Para que as rotinas sejam executadas corretamente existe uma tela de parametros onde é definido
	o endereco do REST, o usuario e senha de autenticaçao do REST e tambem um filtro que facilita
	a busca dos objetos de negócios.
	
	Essa rotina nao cria tabela, parametros ou perguntas, apenas utiliza uma tabela temporaria.
