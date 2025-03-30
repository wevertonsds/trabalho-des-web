<!DOCTYPE html>
<html>
    <head>
        <title>SomWeb</title>
        <style>
            body {
            background-color: rgb(32, 32, 32);
            color: white;
            border: 2px solid #c9bebe;
            padding: 20px;
            width: 60%;
            margin: auto;
            border-radius: 10px;
            }
            h1 {
                color: grey;
                text-align: center;
                border-top: 2px solid grey;
                border-bottom: 2px solid grey;
                font-style: italic;
                font-family: arial black
            }
            .banda {
                display: flex;
                flex-wrap: wrap;
                width: 60%;
                margin: auto;
                border-radius: 5px;
            }
            .banda:hover {
                transform: scale(1.02);
                border: 5px solid rgba(255, 0, 0, 0.452);
                transition: border 0.1s;
            }
            .logo {
                display: flex;
                flex-wrap: wrap;
                width: 20%;
                padding-top: 10px;
                margin: auto;
            }
            .logo:hover {
                padding-top: 0px;
                transform: scale(1.02);
                border: 5px solid rgba(255, 0, 0, 0.452);
                transition: border 0.1s;
            }
            #foo {
                background-color: grey;
                border: 1px solid white;
                padding: 10px;
                margin: 10px;
            }
            h3 {
                font-family: arial;
                font-size: 15px;
            }

            a {
                text-decoration: none;
                color: black;

            }
            a:hover {
                color: rgba(255, 0, 0, 0.452);
                
            }
            button {
                transition: orange 2.5s;
            }
            button:hover {
                transform: scale(1.02);
            }
            blockquote {
            font-style: italic;
            text-align: center;
            border-left: 5px solid rgba(255, 0, 0, 0.452);
        }
        blockquote:hover {
            transform: scale(1.02);
        }
        #btn {
                display: flex;
                flex-wrap: wrap;
                padding: 20px;
                margin: auto;
                background-color: rgba(255, 0, 0, 0.452);
                font-size: 20px;
                border-radius: 10px;
                color: white;
                transition: background-color 0.5s;
                box-shadow: 1px 2px 5px black;
            }
            #btn:hover {
               background-color: grey; 
               transform: scale(1.025);
            }
            #btn:active {
               border: 2px solid white;
               transition: border 0.5s;
               transform: scale(1.05);
            }
            footer {
                text-align: center;
                border: 1px solid white;
            }
        </style>
    </head>

    <body>

    <h1>Guns N´ Roses</h1>
    
    <img src="img/1.jfif" alt="" class="banda">
    <img src="img/2.jpg" alt="" class="logo">
    
    <div id="foo">

        <h1>weverton</h1>

    <h3>Guns N' Roses é uma lendária banda americana de hard rock formada em Los Angeles em 1985. Seu álbum de estreia, Appetite for Destruction (1987), trouxe sucessos como "Sweet Child o' Mine" e "Welcome to the Jungle", conquistando fama mundial e marcando a história do rock.</h3>
    <h3>A banda é conhecida pela energia explosiva e por misturar estilos como punk, blues e heavy metal. Além disso, suas baladas icônicas, como "November Rain" e "Don't Cry", ajudaram a consolidar sua reputação como uma das maiores bandas de rock.</h3>
    <h3>Apesar de mudanças na formação e controvérsias, Guns N' Roses continua influenciando gerações de músicos e fãs. Com uma trajetória cheia de altos e baixos, a banda mantém seu legado.</h3>

    <h2>
        Músicas icônicas:
    </h2>

    <ol> 
        <li>November Rain - <button><a href="https://www.youtube.com/watch?v=8SbUC-UaAxE" target="_blank">Ouvir agora</a></button></li>
        <li>Knockin' On Heaven's Door - <button><a href="https://www.youtube.com/watch?v=k04tX2fvh0o" target="_blank">Ouvir agora</a></button></li>
        <li>Sweet Child O´ Mine - <button><a href="https://www.youtube.com/watch?v=1w7OgIMMRc4" target="_blank">Ouvir agora</a></button></li>
    </ol>

    <h2>
        Curiosidades da banda:
    </h2>

    <ul>
        <li>A logo da banda tem um significado bem interessante, ele junta elemenos como uma cruz, balas e rosas para mostrar a misura do lado bonito e o agressivo, remetendo a ideia da banda.</li>
        <li>A música Sweet Child O´ Mine naceu de um improviso, Slash estava brincando com um riff na guitarra, sem intenção de criar uma musica, quando Axl Rose começou a escrever a letra inspirado em sua namorada na época.</li>
        <li>O videoclipe de November Rain foi um dos mais caros da época, foi lançado em 1992 e custou cerca de US$1,5 milhão, principalmene por causa as cenas do casameno luxuoso e do solo de Slash no deserto.</li>
    </ul>

    <blockquote>"Cause nothing lasts forever and we both know hearts can change
        And it's hard to hold a candle in the cold November rain." - November Rain</blockquote>

        <button id="btn" onclick="window.open('https://www.youtube.com/watch?v=8SbUC-UaAxE', '_blank')">Ouvir Agora</button>

</div>
    <footer>
        <a href="Desafio 3.html" real="next" target="_self">Clique aqui para ir ao desafio 3</a>
    </footer>
    </body>
</html>