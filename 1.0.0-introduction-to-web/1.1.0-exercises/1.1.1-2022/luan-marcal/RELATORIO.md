## RESPOSTAS RELATÓRIO

**0. O que são APIs.  Para que servem ?**\
	APis ou interface de programação de aplicativo, é responsável por nos conectar, mesclando o backend com o frontend, onde pode ser\
	representada por um garçom, que recebe o pedido do cliente e envia até a cozinha para ser feito, sendo o pedido a informação que\
	o usuário forneceu, a cozinha o banco de dados onde essa informação será armazenada e o garçom a Api.

**1. O que são Verbos HTTP ? Quais são eles e o que cada um faz ?**\
	Http ou Hipertext Tranfer Protocol é uma forma de trafegar dados dentro da web, funciona com o modelo de requisição e resposta, para\
	utilizar destas requisições são utilizados os verbos Http. Os principais verbos Http de requisição são:\
	*Get(retorna os dados de uma requisição);\
	*Post(informa dados que irão causar uma mudança);\
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
	*baixar node-v14.17.3-linux-x64.tar.xz https://nodejs.org/dist/v14.17.3/ \
	*extrair na pasata de instalação;\
	*abrir "nano .bashrc" sem aspas;\
	*acrescentar o comando 
	
	export PATH=LOCAL-DE-EXTRAÇÃO/bin:$PATH
	
**6. O que são gerenciadores de pacotes (software)?**\
	São uma coleção de ferramentas de software que automatiza o processo de instalação, atualização, configuração e\
	remoção de programas de computador. O NPM é uma ferramenta do Node.js para o gerenciamento de pacotes.\
	Ele permite instalar, desinstalar e atualizar dependências em uma aplicação por meio de uma simples instrução na\
	linha de comando.
	
**6.1 Instale os principais gerenciadores de pacote para a linguagem JavaScript em sua máquina. | Listar os comandos que utilizou.**

	npm install -g npm
	npm install -g npm@7.24.1

	curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
	echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
	sudo apt update && sudo apt install --no-install-recommends yarn
	yarn set version 1.22.11
	
**7. Java e JavaScript são a mesma linguagem ? Descreva as diferenças entre essas linguagens e pesquise do porque do nome ser parecido.**\
	Não, são linguagens diferentes, a princípio JavaScript é uma linguagem mais utilizada para front-end e Java back-end, porém com a criação\
	do NodeJs o JavaScript tem ganhado força no back-end também. Os nomes são similares pois aos duas linguagens pertencem a Oracle que por sua
	vez talvez tenha mudado o nome da LiveScript para JavaScript para aproveitar a grande ascenção do Java.
	
**8. Você possui o gerenciador de pacotes da linguagem Python em sua máquina?**\
	Sim possuo.

**8.1 Caso não tenha, instale o principal gerenciador de pacote para a linguagem python. | Listar os comandos que utilizou.**

	sudo apt install pip

**8.2 Para checar se você possui o gerenciador de pacote do python (V maisusculo):**
	
	pip -V
	
**9. O que é linguagem interpretada ? O que é linguagem compilada ? E hibidria ?**\
	**Linguagens Interpretadas**\
	Nesse modelo o código gerado pelo desenvolvedor ao ser executado, ele passa primeiro por um software de interpretação que fará a leitura\
	e na sequência execução dos comandos no sistema operacional, fazendo assim um meio de campo.\
	**Linguagens Compiladas**
	Já nesse caso, o código é passado para um compilador, que será convertido em uma linguagem nativa da máquina, para na sequência ser lido\
	diretamente pelo processador, sem a necessidade de intermediador para a execução. 
	**Linguagens Híbridas**
	São aquelas que implementam as duas formas de leituras, compilado e interpretado, por exemplo o Java que tem um compilador que converte seu\
	código para bytecode e na sequência isso é lido para JVM (Java Virtual Machine) que é basicamente um interpretador, para no final ser\
	executado pelo CPU.

**9.1 Escreva exemplos de linguagens compiladas, interpretadas e hibidrias.**
	**Linguagens Interpretadas**\
	 PHP, Ruby e JS.
	 **Linguagens Compiladas**
	 Assembly, C, Pascal e Fortran.
	 **Linguagens Híbridas**
	 JavaScript, python, Java, Swift.

**9.2 Qual o nome do compilador da linguagem C ?**\
	O mais utilizado por desenvolvedores é o GCC
	
**9.3 Qual o nome do compilador da linguagem Java ?**\
	JavaC.
	
**9.4 Qual o nome do interpretador do bytecode da linguagem java ?**\
	Java Virtual Machine.
	
**9.5 Qual o nome do interpretador da linguagem JavaScript ?**\
	Engine JavaScript.
	
**9.6 Qual o nome interpretador da linguagem Python?**\
	Interpretador Python.

**9.7 Python é ou não compilado ? Pesquise e descreva o que encontrar.**\
	Python é uma linguagem interpretada mas, assim como Java, passa por um processo de compilação, digamos que ela seja híbrida.
	
**10. O que é POO em programação?**\
	POO(Programação Orientada a Objetos) é um modelo de análise, projeto e programação baseado na aproximação entre o mundo real\
	e o mundo virtual, através da criação e interação entre objetos, atributos, códigos, métodos, entre outros.
	
**10.1 Java é totalmente POO. O que é uma classe e o que é um objeto ?**\
	Classe é a definição de um objeto, e os objetos são diferentes modelos, por exemplo uma marca produz tênis, sapatos e chinelos,\
	a marca pode ser considerada a classe, já os acessórios são os objetos.
	
**10.2 O que é a JVM, JRE e a JDK ? Descreva.**\
	**JVM -** Máquina vitual Java, é um programa que processa os aplicativos Java para serem executados.\
	**JRE -** Java Runtime Environment, é o ambiente de execução do Java.\
	**JDK -** Java Development Kit, pode ser considerado as ferramentas de desenvolvimento Java.
	
**10.3 Quais os principais gerenciadores de pacote da linguagem java ?**\
	NPM e Yarn.
	
**10.4 Instale o Open JDK 11 em sua máquina. | Listar os comandos que utilizou.**
	
	sudo apt install default-jdk
	java --version
	
	
**11. O que é uma IDE, o que é um editor de texto ?**\
	Uma IDE possuí todas as ferramentas necessárias para o desenvolvimento de uma determinada ferramenta, já o editor de texto\
	apenas facilita a edição de códigos.
	
**11.1 Vs Code é uma IDE ou um editor de Texto ?**\
	É um editor de texto que possuí algumas funcionalidades a mais com plugins.
	
**11.2 Instale o Vs Code em sua máquina.**\
	Ok.
	
**11.3 IntelliJ é uma IDE ou editor de texto ?**\
	Uma IDE escrita em Java.
	
**11.4 Instale o IntelliJ em sua máquina**
	Ok.
	
**12. O que é docker ?**\
	 É uma tecnologia de containerização para criação e uso de containers Linux, sua aplicação é open source.
	 
**12.1 Quais suas vantagens ?**
	Sua vantagem é permitir uma gestão dos recursos podendo agilizar o processo de criação e manutenção.
	
**12.1 Instale o Docker em sua máquina. | Listar os comandos que utilizou.**
	
	sudo apt-get install  curl apt-transport-https ca-certificates software-properties-common
	curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
	






	

	
