# Curso Intermediário de Angular - Digital Innovation One

Esse curso foi feito para a plataforma [Digital Innovation One](https://digitalinnovation.one/)

O curso consiste em um sistema de filmes, com a possibilidade de cadastros, edições, listagem e visualização dos filmes.

![Menu](https://user-images.githubusercontent.com/59884552/78418675-e153a400-7614-11ea-9fa2-27fa17b3b3e2.png)
![Filmes](https://user-images.githubusercontent.com/59884552/78418676-e284d100-7614-11ea-8f41-ca1a8a292109.png)
![Filtro](https://user-images.githubusercontent.com/59884552/78418677-e31d6780-7614-11ea-826e-c6534f192939.png)
![Form](https://user-images.githubusercontent.com/59884552/78418679-e31d6780-7614-11ea-910e-93b3d6ba3a75.png)

## Instalação

1. clone o repositório `git clone git@github.com:RenanRB/curso-angular.git`
2. Entre no projeto e instale as dependencias `npm install`

## Ambiente Local

Execute `ng serve` para que o projeto suba localmente. Acesse a url `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código

## Simulando o Back-end

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

## Gerendo componente

Execute `ng generate component nome-do-componente` para criar um novo componente. Você também pode usuar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

