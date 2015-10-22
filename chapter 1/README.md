# Chapter 1

### WebServer Setting

1. Open command prompt window. (powershell or cmder)
2. Install express generator.

    ```
    $ npm install express-generator -g
    ``` 
    
3. Move project directory.
4. Make server directory and move.
5. Creates an Express app.

     ```
    $ express -e
    $ npm install
    ```    
    
6. Start WebServer.

     ```
    $ npm start (or node .\bin\www)
    ```    
    
7. Edit app.js, express static path.
    
     ```javascript
    app.use(express.static(path.join(__dirname, '../')));
    ```
 
### WebClient Setting

1. Open command prompt window. (powershell or cmder)
2. Move project directory.
3. Install HTML5 Boilerplate. [download](https://html5boilerplate.com/)
4. Install Bootstrap. [download](http://getbootstrap.com/)
5. Open browser, go [http://localhost:3000](http://localhost:3000)
