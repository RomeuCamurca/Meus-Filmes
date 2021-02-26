# Meus-Filmes

## CRUD de gerenciamento de filmes feito com algular no front-end e JSON Server como um MockServer no back-end.

## Demonstração:

![](captured.gif)

## Como executar os projetos:

1. clone o repositório `$ git clone https://github.com/RomeuCamurca/Meus-Filmes.git`

- Para executar o Back-end:

O servidor será um MockServer, no caso o JSON Server

Para mais informações sobre documentação e usabilidade:

[MockServer](https://www.mock-server.com/#what-is-mockserver)

[JSON-Server](https://github.com/typicode/json-server)

Basicamente com o JSON Server é possível Obter uma API REST totalmente falsa com codificação zero de forma extramamente rápida.

Para Instalar o JSON Server execute:

`$ npm install -g json-server` Para instalar globalmente ou
`$ npm install json-server` Na pasta raiz do seu projeto angular para usar somente no projeto em questão.

Depois de instalado, Crie um arquivo db.json por exemplo na raiz do seu projeto com alguns dados, exemplo:

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

Para rodar o JSON Server execute: `$ json-server --watch db.json`.

- Para executar o Front-end:

Pode-se usar o comando `$ npm install` para instalar as dependências e `$ ng serve` para rodar a aplicação angular.

Para mais informações sobre o angular: [Leia-me](https://angular.io/)

### Idealização do Projeto

RenanRB: https://github.com/RenanRB/curso-angular

### :memo: License

This project is developed under the MIT license. See the [LICENSE](LICENSE) file for more details.