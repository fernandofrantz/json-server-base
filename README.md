# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth), existem 3 endpoints que podem ser utilizados para cadastro e 2 endpoints que podem ser usados para login.

### Fórum

POST /forum
GET /forum

em fórum é possível fazer a criação de fórums de discussão e de ajuda para demais usuarios da plataforma, onde eles se ajudam por meio de perguntas postadas e vendo quais as respostas possíveis para resolução de um determinado problema, apenas usuários logados poderão acessar, ler e escrever no fórum.

### News

POST /news
GET /news

como um mini canal de notícias, onde os usuários cadastrados podem escrevê-las e postá-las em uma página para apresentação aos demais, eles sendo usuários cadastrados ou não. O acesso à leitura é de todos.

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"
