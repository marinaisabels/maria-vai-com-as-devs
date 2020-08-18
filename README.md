 <img style="border-radius: 50%;" src="https://raw.githubusercontent.com/marinaisabels/maria-vai-com-as-devs/master/serasa_mulheres.jpg" width="400px;" alt=""/>

### Processo de Seleção Programa Maria vai com as Devs
_____
## 💻 Sobre o projeto

 Apresentar uma solução que ajude a melhorar a vida financeira dos brasileiros e brasileiras.
 O projeto consiste em criar um site responsivo para auxiliar no Controle de Gastos mensal.
---

## ⚙️ Funcionalidades

- Possibilitar que um único usuário possa administrar diversos navers.
 - Autenticação

      - (Signup) Rota de cadastro 
        - Deverá receber email e senha e criar novo registro no banco

      - (Login) Rota para poder logar no sistema
        - Deverá retornar um token [JWT](https://jwt.io/) para o usuário ter acesso à outras rotas
     - (Index) Rota para listagem de cadastro de usuários

     - (Show) Rota para detalhar informações de um único naver através de seu identificador

     - (Delete) Rota Para Deletar usuário.

    - (Update) Rota Para Atualização de informações do usuário.

---

## 🚀 Como executar o projeto

Esse é um projeto de Backend feito utilizando NodeJS, Express, Typescript e MySQL. Além disso, ele segue uma arquitetura baseada em MVC, com 3 camadas simples:

- Controller: responsável pela comunicação com agentes externos (como o Frontend)
- Model: responsável pela representação das nossas entidades
- Business: responsável pela lógica de negócio


### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone git@github.com/marinaisabels/teste-navedex/

# Acesse a pasta do projeto no terminal/cmd
$ cd desktop

# Vá para a pasta 
$ cd projeto

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# O servidor inciará na porta:3000 - acesse http://localhost:3000

```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:
 
([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[KnexJS](http://knexjs.org/)**
-   **[ts-node](https://github.com/TypeStrong/ts-node)**
-   **[dotENV](https://github.com/motdotla/dotenv)**
---

## 🖱️ Documentação do Projeto
- [Postman](https://documenter.getpostman.com/view/10578922/T1DpDdfv?version=latest)

## Dificuldades 




##  Autoras


---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).
