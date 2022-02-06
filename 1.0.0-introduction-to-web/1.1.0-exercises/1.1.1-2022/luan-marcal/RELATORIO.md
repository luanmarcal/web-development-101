**#Respostas-Relatório:**

**0. O que são APIs.  Para que servem ?**\
	APis ou interface de programação de aplicativo, é responsável por nos conectar, mesclando o backend com o frontend, onde pode ser\
	representada por um garçom, que recebe o pedido do cliente e envia até a cozinha para ser feito, sendo o pedido a informação que\
	o usuário forneceu, a cozinha o banco de dados onde essa informação será armazenada e o garçom a Api.

**1. O que são Verbos HTTP ? Quais são eles e o que cada um faz ?**\
	Http ou Hipertext Tranfer Protocol é uma forma de trafegar dados dentro da web, funciona com o modelo de requisição e resposta, para\
	utilizar destas requisições são utilizados os verbos Http. Os principais verbos Http de requisição são:\
	*Get(retorna os dados de uma requisição);\
	*Post(informa dados qeu irão causar uma mudança);\
	*Put(serve para substituir od dados de uma requisição);\
	*Patch(é utilizado para aplicar modificações parcias em um recurso, diferente do Put);\
	*Delete(remove um recurso específico).

**1.2. Para que o POSTMAN é utilizado?**\
	Postman é uma Api client que facilita aos desenvolvedores criar, compartilhar, testar e documentar APIs. Isso é feito, permitindo aos\
	usuários criar e salvar solicitações HTTP.

**2. O que acontece se voce enviar uma requisição GET pelo POSTMAN a sua githubpage ?**\
	O Postman retorna o código fonte da paǵina solicitada, como um espécie da função "exibir código fonte" dos navegadores, pois quando\
	acessamos as paginas da web estamos realizando uma função Get nelas, a diferença é que os navegadores "traduzem" o código fonte\
	para o site que estamos acessando.

**3. Quando voce acessa uma pagina web pelo navegador, qual é o verbo utilizado ?**\
	É utilizado o verbo Get, onde é requisitado o código fonte da página e o navegador "traduz" esse código com o Motor v8 java script,\
	para o site que queremos acessar.

**4. O que são os códigos de status de resposta HTTP ?**\
	Códigos de status de resposta HTTP são indicações do status de uma riquisição, por exemplo quando tentamos acessar uma página web\
	sem estarmos conectados a internet, a pagina nos retorna o código 404 no qual o servidor não pode encontrar o recurso solicitado.
	
**4.1. Quais as classes de agrupamento dos status HTTP ?**\
	*Respostas de informação (100-199);\
    	*Respostas de sucesso (200-299);\
    	*Redirecionamentos (300-399);\
    	*Erros do cliente (400-499);\
   	*Erros do servidor (500-599).
	
**4.2. Quando a requisição HTTP é bem sucedida, qual o código ?**\
	Normalmente a resposta de código bem sucedida é 200 - OK.
	
**4.3. Qual o status HTTP quando você não é autorizado a acessar um recurso ?**\
	403 - Forbidden, cliente não tem direitos de acesso ao conteúdo.
	
**4.4. Listar e descrever a utilização os seguintes códigos de cada agrupamento: 100, 200, 201, 202, 301, 400, 401, 403, 404, 405, 500, 501, 502.**\
	*100 - Continue: significa que o cliente pode continuar com sua requisição.\
	*200 - OK: requisição bem sucedida.\
	*201 - Created: requisição bem sucedida e novo recurso criado.\
	*202 - Accepted: requisição foi recebida mas ainda não foi tomada nenhuma ação sobre ela.\
	*301 - Moved Permanently: significa que a URI(URL) do recurso solicitado foi mudada.\
	*400 - Bad Request: servidor não compreendeu a requisição, sintaxe inválida.\
	*401 - Unauthorized: cliente sem autenticação, autorização negada.\
	*403 - Forbidden: cliente não tem direitos de acesso ao conteúdo.\
	*404 - Not Found: O servidor não pode encontrar o recurso solicitado.\
	*405 - Method Not Allowed: O método de solicitação é conhecido pelo servidor, mas foi desativado e não pode ser usado.\
	*500 - Internal Server Error: O servidor encontrou uma situação com a qual não sabe lidar.\
	*502 - Not Implemented: O método da requisição não é suportado pelo servidor e não pode ser manipulado.
	
**5. O que é Node.js ?**\
	O Node.js se caracteriza como um ambiente de execução JavaScript, é baseado no interpretador v8 do google. Com ele, o usuário\
	pode criar aplicações sem depender do browser para isso.
	
**5.1 Instale-o em sua máquina, versão LTS v14.17.3 | Listar os comandos que utilizou.**\
	**NODE**\
	*baixar node-v14.17.3-linux-x64.tar.xz https://nodejs.org/dist/v14.17.3/; \
	*extrair na pasata de instalação;\
	*abrir "nano .bashrc" sem aspas;\
	*acrescentar o comando "export PATH=LOCAL-DE-EXTRAÇÃO/bin:$PATH" sem aspas.
	
**6. O que são gerenciadores de pacotes (software)?**\
	São uma coleção de ferramentas de software que automatiza o processo de instalação, atualização, configuração e\
	remoção de programas de computador. O NPM é uma ferramenta do Node.js para o gerenciamento de pacotes.\
	Ele permite instalar, desinstalar e atualizar dependências em uma aplicação por meio de uma simples instrução na\
	linha de comando.
	
**6.1 Instale os principais gerenciadores de pacote para a linguagem JavaScript em sua máquina. | Listar os comandos que utilizou.**\
	**NPM**\
	*No termianl "npm install -g npm" sem aspas para instalar versão mais recente do npm.\
	*No terminal "npm install -g npm@7.24.1" sem aspas para versão especificada.\
	**YARN**\
	*No terminal "curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -" sem as aspas.\
	*No terminal "echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list" sem as aspas.\
	*No terminal "sudo apt update && sudo apt install --no-install-recommends yarn" sem as aspas.\
	*No terminal "yarn set version 1.22.11" sem as aspas.
	
**7. Java e JavaScript são a mesma linguagem ? Descreva as diferenças entre essas linguagens e pesquise do porque do nome ser parecido.**\
	.
	

	
