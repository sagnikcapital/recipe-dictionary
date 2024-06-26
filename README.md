# Recipe Book

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.3.3.

![Angular](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT__DpLyuRUlYIwSXn8MGy4bIU-RdXhtYCkSeSKtkrmxQ&s)

## Compatibility
- Node (18.0.0)
- Npm  (10.5.0)
- Angular (ng) (17.3.3)

## Upgrade Node Environment using NVM
```sh
$ nvm ls-remote
```
```sh
$ nvm use 18
```
```sh
$ node --version
```

## Setup firebase for Angular
```sh
$ ng add @angular/fire
```
> Add authentication from a project
```sh
$ npm install firebase
```
## Setup and Installation
> Git clone
```sh
$ git clone 
```
```sh
$ npm install
```
```sh
$ ng serve
```

## Create Angular Environment ts
```sh
$ ng generate environments
```

### Home Page
![Home page](/blobs/home.png)

### Veg category Page
![Veg category](/blobs/Vegtype.png)

### Create Service
```sh
$ ng generate service component/service/name
```

### Create Component
```sh
$ ng generate component component/name
```

### Global scoped CSS Location
> /application/src/styles.css

### Available Icons
> https://ionic.io/ionicons

### Environmental conflagration file
> dotenv.ts
```js
export const API_URL  = process.env['API_URL'];
export const API_KEY  = process.env['apiKey'];
export const AUTH_DOMAIN = process.env['authDomain'];
export const PROJECT_ID = process.env['projectId'];
export const STORAGE_BUCKET = process.env['storageBucket'];
export const MESSAGE_ID = process.env['messagingSenderId'];
export const APP_ID = process.env['appId'];
```

### Preview:
https://recipe-dictionary.vercel.app 
