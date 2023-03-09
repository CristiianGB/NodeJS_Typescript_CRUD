# CRUD Rest API Nodejs with Typescript

Sample Nodejs API with Typescript and Mongodb

## Script:

- npm install
- npm start

## Nodejs Typescript project

Follow these steps to create a new nodejs project with Typescript

- npm init
- tsc --init
- configure tsconfig.json file:
  - "outDir": "./build", ( Redirect output structure to the directory. )
  - "rootDir": "./src", ( Specify the root directory of input files. Use to control the output directory structure with outDir.)

## Mongodb

Mongodb options you can use a local or a remote database: (prefeer local, if you just want to see the project use remote)

- Local
- [Mongodb Atals](https://account.mongodb.com/account/login)

## Endponts:

### User:

- create user : localhost:3000/user/ (crea un usuario)
- get user : localhost:3000/user/userId (coge un único usuario para interactuar con él)
- update user : localhost:3000/user/ ("PUT" para actualizar la información del usuario)

### Posts:

- create post : localhost:3000/post/ (crear posts al servidor de la página)
- get all post : localhost:3000/post/ (coger TODOS los post de la DB)
- get post : localhost:3000/post/postId (coger un único post para interactuar con él)
- delete post : localhost:3000/post/postId (borrar un post)
- update post : localhost:3000/post/ ( actualizar el post que queremos )
