# Api Random Boolean

Api com um end-point que retorna um boolean aleatório

### Pre requisitos

Node  10  ou maior [https://nodejs.org/en/](https://nodejs.org/en/)

### Installing

clone o projeto

    git clone https://github.com/alex3aguiar/random-bool-api
    cd random-bool-api
    
Instale as dependências

    npm install


Este projeto precisa das seguintes variáveis de ambiente:

     NODE_ENV=dev
     CONNECTION_STRING=YOUR_CONNECTION_STRINGS

Durante o desenvolvimento,  variáveis de ambiente podem ser configuradas a partir de um arquivo chamado **".env"**
Use esse comando para criar um .env a partir de um exemplo
`cp .example.env .env`


## Testes

Esse projeto possui testes de integração e teste de unidade na pasta ./test

Para rodar os test

    npm run test
