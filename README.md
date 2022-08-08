<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Crud Car Shop Docker" />

  &#xa0;

  <!-- <a href="https://crudcarshopdocker.netlify.app">Demo</a> -->
</div>

<h1 align="center">Crud Car Shop Docker</h1>

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-funcionalidades">Funcionalidades</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Começando</a> &#xa0; | &#xa0;
  <a href="#memo-afazer">A fazer</a> &#xa0; | &#xa0;
  <a href="https://github.com/Matheushg156" target="_blank">Author</a>
</p>

<br>

## :dart: Sobre ##

Este projeto se trata da criação de uma API com CRUD(Criar, Ler, Atualizar, e Excluir), para gerenciar uma concessionária de veículos utilizando o banco de dados MongoDB.

## :sparkles: Funcionalidades ##

:heavy_check_mark: Persistência de dados com MongoDb;\
:heavy_check_mark: CRUD;\
:heavy_check_mark: Testes;

## :rocket: Tecnologias ##

As seguinte tecnologias foram utilizadas neste projeto:

- [MongoDb](https://www.mongodb.com/pt-br)
- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Docker](https://www.docker.com/pt-br)
- [Chai](https://www.chaijs.com/)
- [Sinon](https://sinonjs.org/)
- [Zod](https://www.npmjs.com/package/zod)


## :white_check_mark: Requerimentos ##

Antes de começar :checkered_flag:, você precisa ter [Git](https://git-scm.com), [Node](https://nodejs.org/en/) e [Docker](https://www.docker.com/pt-br) instalados.

## :checkered_flag: Começando ##

### Com docker ###
```bash
# Clone o projeto
$ git clone git@github.com:Matheushg156/Crud-car-shop-docker.git

# Acesse o diretório do projeto
$ cd crud-car-shop-docker

# Suba os containers
$ npm run compose:up

# O servidor irá inicializar em <http://localhost:3001>

# Execute os testes dentro do container
$ docker exec -it crud-car-shop-docker_backend_1 sh
$ npm run test:coverage
```

### Sem docker ###

```bash
# Clone o projeto
$ git clone git@github.com:Matheushg156/Crud-car-shop-docker.git

# Acesse o diretório do projeto
$ cd crud-car-shop-docker/app/backend

# Instale as dependências
$ npm install

# Inicie o projeto
$ npm start

# O servidor irá inicializar em <http://localhost:3001>

# Execute os testes
$ npm run test:coverage
```

## :memo: A fazer ##

Abaixo seguem alguma melhorias para esse projeto:

- Criação e Integração com o frontend
- Documentação da API com Swagger


Feito por <a href="https://github.com/Matheushg156" target="_blank">Matheus H. Gonzaga</a>

<a href="#top">Back to top</a>
