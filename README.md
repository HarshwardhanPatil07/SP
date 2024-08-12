This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

* Linux or Ubuntu must be there in your system

* NodeJs
  ```sh
  Download Nodejs Version ^ 17.0.0 LTS 
  ```

### Installation
Follow The Installation manual and install dependencies 

1.Clone this repo

2.Install NPM Modules
   ```sh
   cd cpfrontend
   npm install --force
   cd cpBackend
   npm install --force 
   ```
3.Install Lex , Flex and bison
   ```sh
   sudo apt-get update
   sudo apt-get install flex bison
   ```

4.Run Frontend 
   ```js
   cd cpfrontend
   npm run start
   ```
5.Run Backend
```js
   cd cpbackend
   nodemon Server.js
   ```
6. Enter C file Code and Good TO GO
