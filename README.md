# Nodejs
nodemon (restarts server automatically) 

npm install nodemon --save-dev 
npm install nodemon --global
npm view nodemon version
why? 

because we had to do ctrl+c every time to relfect changes in browser, so to get rid of, we install nodemon.

--------------

1- postman

2- dog.ceo 

3- jsonplaceholder

4- fake api 

Make a folder called Express and run command npm init (app.js) and also create app.js and run command npm install express

EXPRESS we dont need headache like in Creating Custom Backend WE HAVE EXPRESS

EXPRESS bhailog, url parsing ma krta ho tum log aur cheeso pa dehan do

npm i nodemon

Tut#71
```
const express = require("express");
const app = express();
const port = 80;
 
app.get("/", (req, res)=>{ 
    res.status(200).send("This is homepage of my first express app with Harry");
});

app.get("/about", (req, res)=>{
    res.send("This is about page of my first express app with Harry");
});

app.post("/about", (req, res)=>{
    res.send("This is a post request about page of my first express app with Harry");
});
app.get("/this", (req, res)=>{
    res.status(404).send("This page is not found on my website cwh");
});

app.listen(port, ()=>{
    console.log(`The application started successfully on port ${port}`);
});

```




























