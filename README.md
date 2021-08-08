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

Criar um novo componente:
>ng g c nomedocomponente

Instalei o Bootstrap:
>npm i bootstrap

Instalei o JQuery:
>npm i jquery@~3.4.1

Instalei o Popper:
>npm i popper.js

Instalei o Font Awesome:
>ng add @fortawesome/angular/fontawesome

Os pacotes usados no Font Awesome: `Free Solid Icons`, `Free Regular Icons`, `Free Brands Icons`.

## Conteúdo bônus
`app-routing.module`: Apresenta todas as rotas do projeto.
`app.component.html`: Apresenta os seletores, os seletores mostram o conteúdo do projeto. 
