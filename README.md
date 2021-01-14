# Tarefas em background utilizando Node.js e Redis

Projeto de “Cadastro de usuário e envio de e-mail de confirmação de cadastro como tarefa em background utilizando Node.js”.
Nesse projeto foi aplicado os conceitos de processamento assíncrono de tarefas utilizando Node.js e Redis.


## 🚀 Recursos Utilizados

* **[Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=vuechatapp_swa-github-gllemos)**
* **[Javascript](https://www.javascript.com/)**
* **[Node.Js](https://nodejs.org/en/)**
* **[Express](http://expressjs.com/pt-br/)**
* **[Redis](https://redis.io/)**
* **[BULL](https://github.com/OptimalBits/bull)**
* **[Mailtrap.io](https://mailtrap.io/)**
* **[Docker](https://www.docker.com/)**


## 🔥 Executando Localmente a Aplicação 

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

### 🌀 Começando... 

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

#### ❗️ Instalando as Dependências (via Windows): 

Abre o cmd (caso esteja utilizando o Windows) navegue até o local onde você clonou o projeto

```
cd "C:\Users\NomeDoComputador\Documents\cloneprojeto"
```

Depois, quando estiver na pasta do projeto, basta digitar no cmd a seguinte instrução: **(dentro da pasta do projeto clonado)**

```
npm install
```

Ao digitar a instrução acima, automaticamente ele irá baixar todas as dependências listadas e definidas no arquivo package.json:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.


### Criar container para o banco Redis com Docker
Execute no terminal para gerar o container:

```
> docker run --name redis -p 6379:6379 -d -t redis:alpine
```

#### 💨 Executando a Aplicação 

Bom, agora na mesma tela do cmd, basta iniciar o server para o projeto ser executado localmente.

```
> npm start
```
Abre um segundo terminal e execute:

```
> npm queue
```


### Dependencias
Não será necessário instalar essas dependências caso você tenha efetuado o clone e as etapas descrito acima. 
```
yarn init -y
yarn add express nodemailer dotenv
yarn add nodemon sucrase -D
yarn add password-generator
yarn add bull
yarn add bull-board
docker run --name redis -p 6379:6379 -d -t redis:alpine

```

