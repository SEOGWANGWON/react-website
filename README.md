# React-nodeJs를 활용한 website

### 웹사이트 설명

nodeJs와 Express를 활용한 back-end 구성 React를 활용한 front-end 구성


### 사용한 도구 

<img style="width: 100px;, height: 100px; background-color: #61DAFB;" src="https://simpleicons.org/icons/nodedotjs.svg"> 
<img style="width: 100px;, height: 100px; background-color: #61DAFB;" src="https://simpleicons.org/icons/react.svg"> 
<img style="width: 100px;, height: 100px; background-color: #61DAFB;" src="https://simpleicons.org/icons/express.svg">



```bash
C:.
│  README.md
│
├─client
│  │  .gitignore
│  │  package-lock.json
│  │  package.json
│  │  README.md
│  │
│  ├─public
│  │      favicon.ico
│  │      index.html
│  │      logo192.png
│  │      logo512.png
│  │      manifest.json
│  │      robots.txt
│  │
│  └─src
│      │  App.css
│      │  App.js
│      │  App.test.js
│      │  AppMain.js
│      │  index.css
│      │  index.js
│      │  logo.svg
│      │  reportWebVitals.js
│      │  setupTests.js
│      │
│      └─Component
│          │  Comment.js
│          │  Footer.js
│          │  Header.js
│          │  Home.js
│          │  MovieList.js
│          │
│          ├─Blog
│          │      Blog.js
│          │
│          ├─Game
│          │      NumberGuessingGame.js
│          │      QuizGame.js
│          │
│          └─Todo
│                  CreatePage.js
│                  ListPage.js
│                  Todo.js
│                  TodoList.js
│                  TodoNoCSS.js
│
└─server
        package-lock.json
        package.json
        server.js

```


## This Repository Command 

```bash
git clone https://github.com/SEOGWANGWON/react-website.git
```



### Client Command

```bash
# Front-End

npx create-react-app client

npm install react-bootstrap bootstrap 

npm install axios
```


```bash
# import link

import 'bootstrap/dist/css/bootstrap.min.css';

import axios from 'axios';
```

### Server Command   

```bath
# Back-End

C:\Users\user1\react-website> mkdir server

C:\Users\user1\react-website> cd server

C:\Users\user1\react-website>server          // your create server.js 

npm init 

npm install express oracledb cors   
```

```bath
# your check package.json folder 

{
  "name": "server",
  "version": "1.0.0",
  "description": "",
  "main": "server.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node server.js"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.18.2",
    "oracledb": "^6.3.0"
  }
}
```
