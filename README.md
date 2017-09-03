## A PoC demo of the RethinkDB Database system to showcase realtime data-fetching and modification abilities ##

--Requirements: 
1) Nodejs ( prferably LTS )
2) RethinkDB
3) Bower
4) Socket.io

--Setup:
1) Install RethinkDB and run command in terminal:
    rethinkDB
    This runs the RethinkDB server

2) Install NodeJS and run command in terminal:
    npm install --save express rethinkdb socket.io async body-parser
    
3) Install bower
    npm install bower -g
    
3) From Terminal open 'RethinkDB/polling-app-using-nodejs-rethinkdb' folder and run command in terminal:
    node app.js
    This run the application
    
    In another terminal window again run the command: node app.js from the same folder to updaet data and check results from two
    simultaneously running user windows.
    
    Open web browser to http://localhost:3000 to view application


