# ReactJS-2022

Projeto ReactJS criado com a ferramenta [Vite](https://vitejs.dev/).
O Vite é uma ferramenta de construção para front-end. Fornece uma criação rápida e opinativa pronta para uso, com API altamente personalizável usando plug-ins. É independente de plataforma, o que significa que oferece suporte a muitas bibliotecas de front-end populares, incluindo React, Vue.

## Criando o Projeto

Para criar um projeto ReactJS usando o Vite, basta executar o comando abaixo:
```
yarn create vite [nome_projeto] --template react-ts
```
Na documentação há outros comando, inclusive com o npm e outros templates. O template utilizado aqui criará um projeto ReactJS com toda a configuração para se utilizar também o Typescript!<br />

Como o Vite não vem com uma pré-definição de qual gerenciador de pacotes será utilizado, após a criação do projeto é necessário instalar as dependências presentes no *package.json* que o Vite gerou. Basta o **yarn install** da vida, ou apenas **yarn**, para isso. Caso use outro gerenciador de pacotes, use o respectivo comando dele!

## Executando o Projeto

Super simples executar o projeto. Afinal não houve mudanças basta o comando ***yarn dev***. Basta acessar o link que aparecer no terminal, possivelmente algo como ***http://localhost:3000/***.
