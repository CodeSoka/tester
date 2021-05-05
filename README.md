# tester
 
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Challenge: Position planet</title>
        <style>
            #greeting {
                background: rgb(255, 255, 0);
                border: 2px solid black;
                font-family: "Comic Sans MS", fantasy;
                padding: 5px;
                width: 262px;
                position:absolute;
                top:10;
                left:10;
                z-index:2;
            }
            
            #creature {
                position:absolute;
                top:14;
                left:52;
                z-index:1;
            }
        </style>
    </head>
    <body>
        
        <img id="planet" src="https://www.kasandbox.org/programming-images/space/planet.png" width="300">
        
        <div id="greeting">
            <p>Hello! Welcome to position planet!</p>
        </div>
        
        <img id="creature" src="https://www.kasandbox.org/programming-images/avatars/mr-pink.png">
        

    </body>
</html>