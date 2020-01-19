# SemanaOmniStack10

## 💡 ideia

O repositório SemanaOmniStack10, foi criado para ser o repositório onde irei guardar o código desenvolvido e tecnologias aprendidas durante a [10° Semana OmniStack](https://rocketseat.com.br/week-10/aulas) da [RocketSeat](https://rocketseat.com.br/). Nessa edição será desenvolvido uma aplicação para procurarmos Devs próximos de nós, sendo assim, possível acessar o GitHub desses Devs, com a intenção de conhece-los. A aplicação terá uma Back-End duas interfaces, sendo elas, web e mobile.

## 🚀 RocketSeat

A [RocketSeat](https://rocketseat.com.br/) é uma empresa que fornece cursos online das tecnologias mais modernas do desenvolvimento web e mobile, possuindo cursos online gratuitos e pagos, também sendo a organizadora da semana OmniStack, onde desenvolvemos uma aplicação durante uma semana, com a ideia de aprender com essa aplicação.

## 👀 Vizualização

### Web

![ ](https://cdn.discordapp.com/attachments/576875163686010911/668580931476389908/OmniStack10WebGIF.gif)

## 🔥 Tecnologias

- JavaScript
- NodeJS
- ReactJS
- React Native  

## 🛠 Inicialização

### Api

Para iniciarmos a nossa ```api```, é necessário fazer uma conta no [Compass | MongoDB](https://www.mongodb.com/download-center/compass) e fazer o download do [MongoDB Compass](https://www.mongodb.com/products/compass), feito isso, devemos criar um novo Cluster. Com o Cluster já criado, ir em ```CONNECT```:

![](https://cdn.discordapp.com/attachments/576875163686010911/668583889790566400/unknown.png)

Após, ir em ```Connect with MongoDB Compass``` na aba ```I have Compass```  e copiar a URL:

![](https://cdn.discordapp.com/attachments/576875163686010911/668584537617334273/unknown.png)

![](https://cdn.discordapp.com/attachments/576875163686010911/668584626310348810/unknown.png)

Já com o MongoDB Compass instalado, basta abrir e adicionar a url copiada no campo, adicionar sua ```<password>``` e clicar em Connect

![](https://cdn.discordapp.com/attachments/576875163686010911/668585181636198423/unknown.png)

Basta agora, criar um novo database

![](https://cdn.discordapp.com/attachments/576875163686010911/668588427125719060/unknown.png)

E por fim, dentro do projeto api, em ```SemanaOmniStack10 > api > src > index.js``` adicionar a seguinte linha

```
mongodb+srv://<username>:<password>@cluster0-yv3gr.mongodb.net/omnistack?retryWrites=true&w=majority
```

![](https://cdn.discordapp.com/attachments/576875163686010911/668589176689524746/unknown.png)

Agora, é necessário fazer o download do [yarn](https://yarnpkg.com/lang/en/), e por fim abrir via Terminal na pasta ```SemanaOmniStack10 > api``` e rodar o comando

```
yarn dev
```

### Web

Para rodar o projeto Web, basta fazer o download o [yarn](https://yarnpkg.com/lang/en/), ir até a pasta ```SemanaOmniStack > web``` e rodar os comandos

```
yarn install
```

e por fim,

```
yarn start
```

onde a aplicação React Js abrirá em seu Navegador padrão automaticamente em ```http://localhost:3000/```
