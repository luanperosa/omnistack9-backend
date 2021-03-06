# omnistack9-backend
Semana Omnistack 9.0 da Rockatseat

![1](https://user-images.githubusercontent.com/50602816/68897299-fedaac80-070b-11ea-8d71-f2a9b7f37f1c.gif)

## :rocket: Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

## 💻 Projeto

O Aircnc é um projeto que visa conectar empresas que querem abrir spots e desenvolvedores que procuram um lugar para trocar ideias com devs, conhecer a empresa e trabalhar lá por um período.

## Como testar o projeto?

Basta clonar este repositorio e no terminal executar os comandos `npm i` para instalar as dependencias, é necessario inserir um arquivo `.env` no repositorio raiz com as variaveis `MONGODB_URI` e `PORT` para executar o banco de dados e a porta do servidor. O banco de dados utilizado no projeto é o <strong>Mongodb</strong>, fique a vontade para instalar localmente seu banco de dados ou utilizar uma solução on-line como o [Mongodb Atlas](https://www.mongodb.com/cloud/atlas) e inserir a url na variavel de ambiente `MONGODB_URI`. Para a variavel `PORT` pode ser utilizado qualquer numero a seu criterio, por convenção geralmente é utilizado porta <strong>3333</strong>.

Executar o comando `npm start` para iniciar a aplicação. Caso queira trabalhar mais no desenvolvimento da API utilize o comando `npm run dev` para utilizar o Nodemon que irá reinicializar o terminal automaticamente durante a alteração dos codigos. 

## Link da API

Está API foi publicada no Heroku, você pode testar a API com esse link abaixo

`https://luan-omnistack9-backend.herokuapp.com/`

Devido a tecnologia utilizada para upload de fotos ser o <strong>multer</strong> não será possivel realizar upload de fotos utilizando essa API pois o multer sobe as fotos em uma pasta local do repositorio. 

## Link para o projeto Web

https://github.com/luanperosa/omnistack9-front-end

## Link para o projeto Mobile

https://github.com/luanperosa/omnistack9-mobile
