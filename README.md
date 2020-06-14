# ReactJS - Desafio 2

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/osvaldokalvaitir/reactjs-desafio2/blob/master/LICENSE)
![](https://img.shields.io/github/package-json/v/osvaldokalvaitir/reactjs-desafio2.svg)
![](https://img.shields.io/github/last-commit/osvaldokalvaitir/reactjs-desafio2.svg?color=red)
![](https://img.shields.io/github/languages/top/osvaldokalvaitir/reactjs-desafio2.svg?color=yellow)
![](https://img.shields.io/github/languages/count/osvaldokalvaitir/reactjs-desafio2.svg?color=lightgrey)
![](https://img.shields.io/github/languages/code-size/osvaldokalvaitir/reactjs-desafio2.svg)
![](https://img.shields.io/github/repo-size/osvaldokalvaitir/reactjs-desafio2.svg?color=blueviolet)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)
![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

Aplicação GitHub Compare usando Create React App, ESLint, prop-types, styled-components, Axios, Moment, Font Awesome e Local Storage.

## Desafio 2

Nesse desafio você irá melhorar a aplicação que desenvolvemos durante o segundo módulo com as seguintes funcionalidades:

- Armazene a lista de repositórios adicionados ao `localStorage` (https://www.w3schools.com/html/html5_webstorage.asp), ou seja, se a página for atualizada ou fechada/aberta a lista de repositórios deve ser a mesma;
- Crie um botão em cada repositório para deletar o mesmo da listagem e remova-o do localStorage também;
- Crie um botão em cada repositório para atualizar os dados dele buscando as novas informações de stars, forks, last commit, etc;

## Índice

- [Capturas de Tela](#capturas-de-tela)

  - [Principal](#principal)

- [Desenvolvimento](#desenvolvimento)

  - [Configuração do Ambiente](#configuração-do-ambiente)

  - [Instalação do Projeto](#instalação-do-projeto)

  - [Execução do Projeto](#execução-do-projeto)

- [Utilizados no Projeto](#utilizados-no-projeto)

  - [Bibliotecas](#bibliotecas)

  - [APIs](#apis)

## Capturas de Tela

### Principal

![Main](/.github/assets/main.png)
Esta é a única tela, onde encontram-se todos os repositórios do GitHub que o usuário pesquisar na caixa de texto, podendo também, atualizar ou remover o repositório.

## Desenvolvimento

### Configuração do Ambiente

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/README.md) e siga `Configuração de Ambiente`.

### Instalação do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/nodejs.md) e siga `Instalação de Projeto`.

### Execução do Projeto

Clique [aqui](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md) e siga `Execução de Projeto para Desenvolvimento` ou `Construção e Execução de Projeto para Produção`.

## Utilizados no Projeto

### Bibliotecas

- [Axios](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/axios.md)

- [Create React App](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/create-react-app.md)

- [eslint-config-airbnb](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-config-airbnb.md)

- [eslint-plugin-import](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-import.md)

- [eslint-plugin-jsx-a11y](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-jsx-a11y.md)

- [eslint-plugin-react](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/eslint-plugin-react.md)

- [Font Awesome](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/font-awesome.md)

- [Moment](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/moment.md)

- [prop-types](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/prop-types.md)

- [styled-components](https://github.com/osvaldokalvaitir/projects-settings/blob/master/nodejs/libs/styled-components.md)

### APIs

- **[GitHub API](https://github.com/osvaldokalvaitir/projects-settings/blob/master/api/github-api.md)**

  - **Rotas**

    - Usuários

      - Busca dados de um repositório pertencente a um usuário
