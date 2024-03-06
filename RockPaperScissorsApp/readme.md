___Copy and Use this link in the .markdown file___  

![image](https://github.com/PhoenixGreen/MyGoProjects/blob/main/RockPaperScissorsApp/Rock%20paper%20scissors%20app.jpg)

## Rock Paper Scissors
This was the first time I've tried to connect all the dots between the basics of Golang and building a functional web app with visual elements. 

The game logic is housed in the rps/rps.go file. This includes the modulus logic for choosing who wins and returning the three main messages:
* Play chose
* Computer chose
* Who won 

This file also connects these messages to json so they can be used in the web browser.

main.go is the starting point for the app, which also functions as the web server, delivering the app on ‘localhost:8080’. When running, this can be called in the web browser address bar. ‘Localhost:8080’ will call the index.html page. Localhost:8080/play will call the json data, which will appear in the javascript console. Using json and javascript, this data is also called in the index.html page as part of the game.

The index.html page houses the look of the web app which includes bootstrap CSS, javascript and HTML page elements.
