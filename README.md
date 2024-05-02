# API "GITHUB SIMPLES"

Esta é uma API simples que simula o GitHub, permitindo operações básicas (CRUD) em repositórios e a capacidade de "curtir" esses repositórios. Utiliza JavaScript, Express e Jest como principais dependências.

## Tecnologias Utilizadas

- NODE
- JAVASCRIPT
- EXPRESS
- JEST

## Funcionalidades

1. Repositórios:
- Criar um novo repositório.
- Listar todos os repositórios.
- Atualizar um repositório existente.
- Não é possível atualizar um repositório que não existe.
- Não é possível atualizar os likes de um repositório manualmente.
- Excluir um repositório.
- Não é possível excluir um repositório que não existe.
2. Curtidas:
- Dar um "like" em um repositório.
- Não é possível dar um "like" em um repositório que não existe.

## Testes

1. Repositórios:
- Deve ser capaz de criar um novo repositório.
- Deve ser capaz de listar todos os repositórios.
- Deve ser capaz de atualizar um repositório.
- Não deve ser capaz de atualizar um repositório que não existe.
- Não deve ser capaz de atualizar manualmente os likes de um repositório.
- Deve ser capaz de excluir um repositório.
- Não deve ser capaz de excluir um repositório que não existe.
2. Curtidas:
- Deve ser capaz de dar um "like" em um repositório.
- Não deve ser capaz de dar um "like" em um repositório que não existe.

## Instalação e execução do projeto

Clone o projeto

```bash
  git clone https://github.com/iamfelipy/rockseat-ignite-nodejs-chapter-i-desafio-3
```

Entre no diretório do projeto

```bash
  cd  rockseat-ignite-nodejs-chapter-i-desafio-3
```

Instale as dependências

```bash
  npm install
```

Inicie o servidor

```bash
  npm run dev
```
