-------------- métodos de start da aplicação (executar o servidor) --------------
"code ." (iniciar o vs code na pasta)
"node index.js" (backend start)
"npm start" (start do frontend e do backend(alterando o arquivo de configuração))
-------------- métodos de start da aplicação --------------



-------------- criando aplicação node --------------
1 - baixar o chocolatey (para baixar o node)

2 - criar a pasta do projeto

3 - "npm init -y" (package.js vai armazenar informações das dependências que serão instaladas no projeto)

4 - "npm install express" (incluir o micro frammework express = cuida das rotas(para não configurar a aplicação do zero))
-------------- criando aplicação node --------------



-------------- criando aplicação react --------------
5 - "npx create-react-app frotend"

6 - "npm install react-icons" (instalar o pacote de ícones do react)

7 - "npm install react-router-dom" (pacote responsável por lidar com as rotas no react)
-------------- criando aplicação react --------------



---------- conectar o frontend com o backend ----------
"npm install axios" (instalar um cliente http que será responsável por fazer as chamadas/consumir a API do backend)
(service é todo tipo de arquivo que vai prover algum tipo de integração com algum serviço externo, aqui nessa caso)
---------- conectar o frontend com o backend ----------



-------------- Ferramentas necessárias --------------
Download Insomnia (para testar as rotas)

"npm install nodemon -D"
"npm start" (agora no modo watch)


---------- configurações para criar html de forma mais ágil ----------
setting.json
{
	"emmet.syntaxProfiles": { "javascript": "jsx" },
	"emmet.includeLanguages": { "javascript": "javascriptreact" },
}
---------- configurações para criar html de forma mais ágil ----------


"npm install knex" (cuidar da parte de comunicação com o banco de dados)
"npm install sqlite3" (driver de acordo com o banco de dados que a gente vai utilizar)
"npx knex init" (criar um arquivo com as configurações de acesso ao banco de dados)
"npx knex migrate:make nomemigration" (criar migration que é uma espécie de ferramenta de versionamento para o banco de dados) 
"npx knex migrate:latest" (executar a migration)
"npx knex migrate:rollback" (retirar a migration)
"npx knex migrate:status" (listas as migrations que já foram executadas)
-------------- Ferramentas necessárias --------------



-------------- Informações para lembrar / curiosidades --------------
Métodos HTTP:
*GET: Buscar uma informação do back-end
*POST: Criar uma informação do back-end
*PUT: Alterar uma informação do back-end
*DELETE: Deletar uma informação do back-end

Tipos de parâmetros:
*Query Params: Parâmetros nomeados enviados na rota após "?" (filtros, paginação)
*Route Params: Parâmetros utilizados para identificar recursos
*Request Body: Corpo da requisição, utilizado para criar ou alterar recursos

*headers...

notion -> bacana
-------------- Informações para lembrar / curiosidades --------------