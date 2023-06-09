# Teste técnico Gabriel Leiria 

## Descrição
Este é o meu projeto web incrível que faz coisas incríveis.

## Configuração

### Pré-requisitos
Certifique-se de ter o Node.js instalado em sua máquina.

### Instalação
1. Clone este repositório 
```
git clone https://github.com/leiriads/Nodejs/AppWeb
```
2. Navegue até o diretório do projeto clonado 
``` 
cd AppWeb
```
3. Estando dentro da pasta AppWeb.
4. No cmd digite: 
```code . ``` 
para abrir o vscode. contendo apenas as pastas backend e frontend.
5. Assim deve ficar:


![vscode1](https://github.com/Leiriads/Teste/assets/89768557/62807a05-27d1-4a58-be1f-ab2197fb4433)


6. Ainda com o terminal aberto navegue até o diretório backend:
 ``` 
 cd backend
 ```
7. O comando a seguir só vai funcionar dentro da pasta backend.
8. Execute o comando 
```
npm install
``` 
9. Este comando irá instalar todas as dependências do projeto.


### Configuração do Banco de Dados
### Variáveis de Ambiente
Edite o arquivo ```.env ``` na raiz do projeto conforme o necessário, deixei setado como configurei no meu computador:

```
MYSQL_HOST= localhost
MYSQL_USER= root
MYSQL_PASSWORD=
MYSQÇ_DB=crud
MYSQL_PORT= 3306
JWT_SECRET= s8p38US3su38Unsk3i9iKOKOiu883u93j83h0330h3h30d
PORT= 3333
```

## Criando o Banco de Dados
1. Dentro do diretório backend Execute o comando 
```
npm run sequelize
```
2. Esse comando roda um script que cria um banco de dados Mysql com nome crud e suas tabelas.
3. Recomendo não alterar o nome  ```MYSQÇ_DB=crud ``` do .env pois o script ja esta setado para criar um database com esse nome.

### Execução
1. Dentro da pasta backend Execute o comando:
 ```
 npm start
 ```
para iniciar o servidor.
2. O servidor estará em execução na porta especificada no arquivo `.env`.

### Desenvolvimento
1. Dentro da pasta backend Execute o comando: 
```
npm run dev
``` 
2. Este comando irá iniciar o servidor no modo de desenvolvimento.
3. O servidor reiniciará automaticamente sempre que houver alterações nos arquivos.

### Endpoints
1. Os endpoit da API estarrão disponíveis em http://localhost:3333
2. Porém as rotas estão com Middlewares de autenticação de usuário via token JWT para acesso das mesmas.
3. Exemplo de uma das rotas : 
```
http://localhost:3333/produtos
```
## Frontend

1. Instale  o plugin LiveServer no seu Vscode
2. Dentro da pasta Frontend procure o arquivo `index.html` que não está dentro de nenhuma pasta.

![vscode](https://github.com/Leiriads/Teste/assets/89768557/30f683a9-865a-4297-8557-07d64ecd87e3)


3. Clique com o botão direito sobreo mesmo e abra com LiveServer.
4. Você deve cair em uma pagina de Login.
5. Não esqueça de ligar a Api antes de acessar o frontend.
6. O mesmo está configurado para buscar os dados na api através do localhost.


## Recursos

- [Express](https://expressjs.com/) - Framework para construção de aplicações web.
- [Sequelize](https://sequelize.org/) - ORM para manipulação do banco de dados.
- [MySQL2](https://www.npmjs.com/package/mysql2) - Pacote de driver MySQL para Sequelize.
- [Nodemon](https://nodemon.io/) - Monitora alterações nos arquivos e reinicia o servidor automaticamente.
- [Dotenv](https://www.npmjs.com/package/dotenv) - Carrega variáveis de ambiente a partir de um arquivo `.env`.
- [Cors](https://www.npmjs.com/package/cors) - Middleware para habilitar CORS (Cross-Origin Resource Sharing).
- [Jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) - Biblioteca para geração e verificação de tokens JWT.
- [Bcrypt](https://www.npmjs.com/package/bcrypt) - Biblioteca para criptografia de senhas.
- [Faker](https://www.npmjs.com/package/faker) - Biblioteca para geração de dados falsos.

## Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões, abra uma issue ou envie um pull request.

## Licença
Signotech.
