<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Not Wrong</title>

    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
    <meta name="apple-mobile-web-app-capable" content="yes">

    <style>
        .app {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
            text-align: center;
            font-family: sans-serif;
            color: rgb(0, 0, 0);
        }

        .bg {
            background: #ffffff;
            background-image: url("Assetination/garageBG2.png");
            background-position: center;
            background-size: cover;
            filter: blur(0px);
            transform: scale(1.5);
            width: 100%;
            height: 100%;
            z-index: 0;
            position: fixed;
            left: 0;
            top: 0;

        }

        img {
            padding: 10px;
            max-width: 100%;
            max-height: 120%;

        }

        h3 {
            font-size: 30px;
            margin: 50px;
            height: 120px;
        }

        p {
            background: white;
            color: black;
            padding: 25px;

        }

        button {
            background: black;
            color: white;
            padding: 15px;
            border: none;
            transition: 100ms;
            outline: none;
            height: 50px;
            margin: 5px;

        }


        button:hover {
            background: white;
            color: black;
        }

        .logo {
            height: 20%;
        }

        .title,
        .text,
        .button {
            height: 40%;
        }

        .footer {
            z-index: 2;
            width: 100%;
            text-align: center;
            position: fixed;
            bottom: 0;
            font-family: sans-serif;
            opacity: 0.5;
            padding: 5px;
            left: 0;
            font-size: 10px;
        }

        a {
            text-decoration: none;
            color: rgb(0, 0, 0);
            height: 150px;
        }
    </style>
</head>

<body>




    <div class="app">
        <div class="logo">
            <img src="Assetination/not wrong+.jpg">
        </div>
        <a class="title">
            <h3 id="peter"></h3>
        </a>
        <div>
            <img id="ex" src="explain00.png">
        </div>
        <div class="button">
            <button onClick="explain();">Erklärung</button>
            <button onClick="random();">Next</button>
        </div>


    </div>

    <script type="text/javascript">

        document.body.style.backgroundColor = white

        var i = 1
        var explain00 = 'explain00.png'
        var explain01 = 'explain01.png'
        var explain02 = 'explain02.png'
        var explain03 = 'explain03.png'
        var explain04 = 'explain04.png'
        var explain05 = 'explain05.png'
        var explain06 = 'explain06.png'
        var explain07 = 'explain07.png'
        var explain08 = 'explain08.png'
        var explain09 = 'explain09.png'
        var explain10 = 'explain10.png'

        var quote01 = "Wenn hinter Fliegen Fliegen fliegen, fliegen Fliegen Fliegen nach."
        var quote02 = "Buffalo buffalo Buffalo buffalo buffalo buffalo Buffalo buffalo."
        var quote03 = "The old man the boat."
        var quote04 = "Time flies like an arrow, fruit flies like a banana."
        var quote05 = "The complex houses married and single soldiers and their families."
        var quote06 = "The rat the cat the dog bit chased escaped."
        var quote07 = "That that is is. That that is not is not. Is that it? It is."
        var quote08 = "This exceeding trifling witling, considering ranting criticizing concerning adopting fitting wording being exhibiting transcending learning, was displaying, notwithstanding ridiculing, surpassing boasting swelling reasoning, respecting correcting erring writing, and touching detecting deceiving arguing during debating."
        var quote09 = "Bismarck biss Mark, bis Mark Bismarck biss."
        var quote10 = "English can be understood through tough thorough thought, though."

        function random() {
            let j = i++

            document.getElementById("ex").src = explain00

            if (i == 2) {
                document.getElementById("peter").innerHTML = quote01
                console.log(quote01)
            }
            else if (i == 3) {
                document.getElementById("peter").innerHTML = quote02
            }
            else if (i == 4) {
                document.getElementById("peter").innerHTML = quote03
            }
            else if (i == 5) {
                document.getElementById("peter").innerHTML = quote04
            }
            else if (i == 6) {
                document.getElementById("peter").innerHTML = quote05
            }
            else if (i == 7) {
                document.getElementById("peter").innerHTML = quote06
            }
            else if (i == 8) {
                document.getElementById("peter").innerHTML = quote07
            }
            else if (i == 9) {
                document.getElementById("peter").innerHTML = quote08
            }
            else if (i == 10) {
                document.getElementById("peter").innerHTML = quote09
            }
            else if (i == 11) {
                document.getElementById("peter").innerHTML = quote10
            }
            else if (i >= 12) {
                i = 1
                random()
            }
            document.body.style.webkitBackgroundSize = "cover"
            console.log(i)
        }

        function explain() {
            if (document.getElementById("peter").innerHTML == quote01) {
                document.getElementById("ex").src = explain01
            }
            else if (document.getElementById("peter").innerHTML == quote02) {
                document.getElementById("ex").src = explain02
            }
            else if (document.getElementById("peter").innerHTML == quote03) {
                document.getElementById("ex").src = explain03
            }
            else if (document.getElementById("peter").innerHTML == quote04) {
                document.getElementById("ex").src = explain04
            }
            else if (document.getElementById("peter").innerHTML == quote05) {
                document.getElementById("ex").src = explain05
            }
            else if (document.getElementById("peter").innerHTML == quote06) {
                document.getElementById("ex").src = explain06
            }
            else if (document.getElementById("peter").innerHTML == quote07) {
                document.getElementById("ex").src = explain07
            }
            else if (document.getElementById("peter").innerHTML == quote08) {
                document.getElementById("ex").src = explain08
            }
            else if (document.getElementById("peter").innerHTML == quote09) {
                document.getElementById("ex").src = explain09
            }
            else if (document.getElementById("peter").innerHTML == quote10) {
                document.getElementById("ex").src = explain10
            }

        }
    </script>
    <script defer=""></script>
    </div>
    </div>
    <div class="footer">
        <a></a>
    </div>
</body>

</html>