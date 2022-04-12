# lb_01
Learn Loopback framework.
* [Get Started](https://loopback.io/doc/en/lb4/Getting-started.html)

# 1. Setup
```sh
$ nvm ls
->     v16.13.1
default -> lts/gallium (-> v16.13.1)
$ npm i -g @loopback/cli
$ lb4 app
? Project name: lb_01
? Project description: workspace_js
? Project root directory: lb_01
? Application class name: Lb_01Application
? Select features to enable in the project Enable eslint, Enable prettier, Enable mocha, Enable loopbackBuild, Enable vscode, Enable dock
er, Enable repositories, Enable services
? Yarn is available. Do you prefer to use it by default? Yes
Application lb_01 was created in lb_01.

Next steps:

$ cd lb_01
$ yarn start

$ git init
$ git remote add origin git@github.com:rwibawa/lb_01.git
$ git add -A
$ git status
$ git commit -m "init repo"
$ git push -u origin master
```

## 2. Add Controller
```sh
$ lb4 controller
? Controller class name: hello
Controller Hello will be created in src/controllers/hello.controller.ts

? What kind of controller would you like to generate? Empty Controller
   create src/controllers/hello.controller.ts
   update src/controllers/index.ts

Controller Hello was/were created in src/controllers
```