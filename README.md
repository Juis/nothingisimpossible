impossible
==========

Instala��o:

1 - node.js

WINDOWS

> baixe o http://nodejs.org/ e coloke em uma pasta onde irá utilizar;

MAC

> brew install node

2 - NPM pacotes

> entre na pasta onde foi dizipado o node.js e execute o comando "node"
abrindo o console do node.js execute os comandos "npm ( nome do pacote a ser instalado ) install -g"

3 - NPM pacote framework express

npm express install -g

4 - instalando e executando o servidor o mongodb

 WINDOWS

> baixe o http://www.mongodb.org/ e coloke em uma pasta dentro de node.js ( para ficar organizado )
va para a pasta onde o mongodb foi descompactado e execute o comando "mongo"

> "uses nothingisimpossible" => criando o banco de dados
> "db.usercollection ({"login": "juis", "senha":"123"}) => criado os dados para poder criar o banco fisico

> cria uma pasta data na raiz do projeto

> no console va para a pasta bin do mongodb e execute o comando: "mongod --dbpath raiz-do-projeto\data"

 MAC

na raiz do terminal digite: 
> cd /usr/local/

logo apos digite: 
> brew install mongodb

5 - Com as configurações do ponto 4 deve está pronto para utilizar o projeto.

Bibliografia:

> boas praticas javascript: http://jsfiddle.net/2SMEN/

> http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/

> https://github.com/emberjs-addons/ember-bootstrap

> https://github.com/yeoman/generator-ember

> http://nodebr.com/nodejs-e-mongodb-introducao-ao-mongoose/

> https://github.com/bpdp/express-mongoose-mvc

> https://github.com/madhums/node-express-mongoose-demo
