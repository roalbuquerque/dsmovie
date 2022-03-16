# DS Movie 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/roalbuquerque/dsmovie/blob/main/LICENSE) 

# Sobre o projeto

O 'DS Movie' é uma aplicação full stack web e mobile construída durante um evento de uma semana organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

A aplicação é referente a um catalogo de filmes onde o usuário pode classificar o filme com uma nota de 1 a 5. 
O Frontend foi construído em React e esta hospedado no netlify, e o backend foi construído em Spring boot e esta no Hiroku, os dados estão sendo armazenados em um banco de dados 'postgre SQL'. 

⚡ Observação: O projeto backend está hospedado no Hiroku, e como se trata da versão gratuita, ela adormece a aplicação caso não esteja em uso por 30 minutos.
Neste caso ao acessar o link abaixo, aguardar alguns segundos para que as informações carreguem. 😄

https://albuquerque-dsmovie.netlify.app/

## Layout mobile
![Mobile 0](https://github.com/roalbuquerque/dsmovie/blob/main/assets/Mobile01.jpeg)
![Mobile 1](https://github.com/roalbuquerque/dsmovie/blob/main/assets/Mobile02.jpeg) 
![Mobile 2](https://github.com/roalbuquerque/dsmovie/blob/main/assets/Mobile03.jpeg) 
![Mobile 4](https://github.com/roalbuquerque/dsmovie/blob/main/assets/Mobile04.jpeg) 

## Modelo conceitual
![Modelo Conceitual](https://github.com/roalbuquerque/dsmovie/blob/main/assets/dsmovie-dominio.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
  ### Dependências:
  (JPA, H2, Postgres, Security)   
## Front end
- TypeScript, bootstrap
- ReactJS
## Ferramentas de Apoio
- Postman
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/roalbuquerque/dsmovie

# entrar na pasta do projeto back end
cd backend

# Abrir o projeto no "Spring Tool Suite 4"

# executar o projeto
Botão direito sobre a classe "DsmovieApplication.java" e >Run As>Spring Boot App

# o que acontece depois de executar o projeto backend
O banco será criado conforme scripts do arquivo import.sql

```

## Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/roalbuquerque/dsmovie

# entrar na pasta do projeto front end web
cd frontend

# instalar dependências
yarn install
ou
npm install

# executar o projeto
yarn start
ou
npm start

# o que acontece depois de executar o ultimo comando:
A aplicação será aberta no navegador

```

# Autor

Rafael de Oliveira Albuquerque

📫 Você pode me encontrar aqui:
<p align="left">
  <a href="https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" alt="Linkedin">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rafaeloliveiraalbuquerque/" /></a>

