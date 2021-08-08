# Desenvolvendo seu blog com as tecnologias de Java e Angular

## Pré-requisitos
- Lógica de programação.
- HTML5, CSS3.
- JavaScript.

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

Você gostaria de usar os recursos de rotas do Angular? `sim`.
Que formato de folha de estilo você quer usar? `CSS`.

Criei o projeto:
>ng new blog

Subir a aplicação:
>ng serve
