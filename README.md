# Catálogo de Filmes em Angular

O projeto consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização de filmes de outros usuários.

## Instalação

1. Clone o repositório `git clone git@github.com:beletate/catalogo-filmes-angular.git`
2. Entre no projeto e instale as dependências `npm install`

## Ambiente Local

Execute `ng serve` ou `npm start` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

