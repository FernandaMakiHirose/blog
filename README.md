# Desenvolvendo seu blog com as tecnologias de Java e Angular

## Pré-requisitos
- Lógica de programação.
- HTML5, CSS3.
- JavaScript.

## Comandos para executar no projeto
Dentro da pasta `blog` da pasta `frontend`:
>npm install

## Como eu desenvolvi esse projeto?
### Backend
Habilitei o Package.json:
>npm init-y

Habilitei as dependências:
>npm i json-server 

Criei um script no `package.json chamado` start:
>"scripts": {"start": "json-server --watch db.json --port 3000"} <br>

Obs: o nome da aplicação é `json-server`, o arquivo é o `db.json` na porta `3000`. <br>

Criei o arquivo `banco.json` que é usado como banco de dados.

### Frontend 
Instalei o Angular:
>npm i -g @angular/cli

Você gostaria de usar os recursos de rotas do Angular? `sim`. <br>
Que formato de folha de estilo você quer usar? `CSS`.

Criei o projeto:
>ng new blog

Subir a aplicação:
>ng serve

Criar um componente:
>ng g c nomedocomponente

Criar um serviço:
>ng g s pasta/nomedoserviço

Instalei o Bootstrap:
>npm i bootstrap

Instalei o JQuery:
>npm i jquery@~3.4.1

Instalei o Popper:
>npm i popper.js

Instalei o Font Awesome:
>ng add @fortawesome/angular/fontawesome <br>

Os pacotes usados no Font Awesome: `Free Solid Icons`, `Free Regular Icons`, `Free Brands Icons`.

## Conteúdo bônus
`app-routing.module`: Apresenta todas as rotas do projeto. <br>
`app.component.html`: Apresenta os seletores, os seletores mostram o conteúdo do projeto. <br>
`angular.json`: Nos `styles` adicionei o path do Bootstrap, nos `scripts` adicionei o path do Jquery, do Bootstrap e do Popper. <br>
`navbar.component.html`: Adicionei o conteúdo do navbar, peguei o HTML na documentação do Bootstrap, coloquei o conteúdo dentro de uma `div` e adicione as páginas referentes aos links. <br>
`footer`: Apresenta o footer do projeto, onde adicionei os ícones do Font Awesome, junto com um CSS. <br>
`home`: Apresenta a home do projeto, onde adicionei uma breve introdução do projeto e um parallax. <br>
`contato`: Apresenta o contato do projeto, onde adicionei um formulário. <br>
`Post.ts`: Faz a comunicação com o Backend. <br>
`app.module.ts`: Importei o HttpClientModule. <br>
`post.service.ts`: Apresenta os métodos dos posts.
`feed.component.ts`: Apresenta a ligação com o `post.service.ts`, importando o service e o model.
