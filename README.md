# SOLID introduction - Ignite NodeJS

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Solid&message=Introduction&color=blueviolet&style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/MrRioja/ignite-introduction-solid?color=blueviolet&logo=License&style=for-the-badge"/>
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/MrRioja/ignite-introduction-solid?color=blueviolet&logo=TypeScript&logoColor=white&style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/MrRioja/ignite-introduction-solid?color=blueviolet&style=for-the-badge">
</p>
<br>

<p align="center">
  <a href="#sobre">Sobre</a> •
  <a href="#solid-introduction">SOLID Introduction</a> •
  <a href="#instalação">Instalação</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#autor">Autor</a>  
</p>

## Sobre

Projeto proposto no desafio complementar do módulo II da trilha do bootcamp de NodeJS da Rocketseat cujo objetivo foi conhecer e colocar em prática alguns dos princípios do SOLID.

## SOLID Introduction

O intuito dessa API é ser uma aplicação de listagem e cadastro de usuários. Para que a listagem de usuários funcione, o usuário que solicita a listagem deve ser um admin (mais detalhes ao longo da descrição).
O projeto é simples pois o desafio aqui foi praticar a arquitetura da aplicação colocando em pratica os princípios SOLID ensinados durante o módulo.

### Rotas da API

<details>
  <summary>GET <code>/users</code></summary>
  <br>
  A rota recebe, pelo header da requisição, uma propriedade <code>user_id</code> contendo o <code>id</code> do usuário e retornar uma lista com todos os usuários cadastrados. O <code>id</code> é usado para validar se o usuário que está solicitando a listagem é um admin. O retorno da lista deve ser feito apenas se o usuário for admin.
</details>

<details>
  <summary>GET <code>/users/:user_id</code></summary>
  <br>
  A rota recebe, nos parâmetros da rota, o <code>id</code> de um usuário e devolver as informações do usuário encontrado pelo corpo da resposta.
</details>

<details>
  <summary>POST <code>/users</code></summary>
  <br>
  A rota recebe <code>name</code> e <code>email</code> dentro do corpo da requisição para que seja possível cadastrar um usuário.
</details>

<details>
  <summary>PATCH <code>/users/:user_id/admin</code></summary>
  <br>
  A rota deve receber, nos parâmetros da rota, o <code>id</code> de um usuário e transformar esse usuário em admin.  
</details>

## Instalação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disso é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/ignite-introduction-solid.git

# Acesse a pasta do projeto no terminal/cmd
$ cd ignite-introduction-solid

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn dev

# Execute os testes da aplicação
$ npm run test
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn test

# O servidor inciará na porta 3333 - acesse <http://localhost:3333>
```

## Tecnologias

<img align="left" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="75" />

<img align="left" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="75"/>

<br><br><br>

## Autor

<div align="center">
<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/55336456?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d" />
<h1>Luiz Rioja</h1>
<strong>Backend Developer</strong>
<br/>
<br/>

<a href="https://linkedin.com/in/luizrioja" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/mrrioja" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:lulyrioja@gmail.com?subject=Fala%20Dev" target="_blank">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://api.whatsapp.com/send?phone=5511933572652" target="_blank">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<a href="https://join.skype.com/invite/tvBbOq03j5Uu" target="_blank">
<img alt="Skype" src="https://img.shields.io/badge/SKYPE-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white"/>
</a>

<br/>
<br/>
</div>
