## BOOTCAMP DESENVOLVEDOR BACKEND IGTI

# 🔐 Facebook Authentication with Node.js and Passport

Este projeto demonstra como integrar autenticação via Facebook usando Node.js, Express e Passport.js.

OBS: A requisição para login redireciona o navegador para o Facebook, onde o usuário deve inserir suas credenciais e autorizar o acesso.

## 🚀 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Passport.js](http://www.passportjs.org/)
- [passport-facebook](http://www.passportjs.org/packages/passport-facebook/)
- EJS (template engine)

## ⚙️ Pré-requisitos

- Node.js instalado
- Conta de desenvolvedor no Facebook
- Criar um **Facebook App** para obter `clientID`, `clientSecret` e configurar o `callbackURL`

## Configuração

Crie um arquivo chamado configFacebook.js com as credenciais do seu aplicativo:

module.exports = {
    clientID: "SUA_CLIENT_ID_DO_FACEBOOK",
    clientSecret: "SEU_CLIENT_SECRET_DO_FACEBOOK",
    callbackURL: "http://localhost:5000/auth/facebook/callback"
};
Obs: Certifique-se de adicionar a URL http://localhost:5000/auth/facebook/callback nas configurações de redirecionamento do seu app no Facebook Developer Portal.

## 🛠️ Instalação

npm start

## Execução

node app.js

