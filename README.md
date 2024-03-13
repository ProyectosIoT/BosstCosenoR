<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            text-align: center;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 15px;
            font-size: 18px;
            border: yes;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s;
        }

        .button:hover {
            background-color: #3498db;
        }

        .button:active {
            transform: translateY(2px);
        }

        #btn10b,
        #btn25b,
        #btn50b,
        #btn75b,
        #btn90b,
        #btnApagarb {
            background-color: #34495e;
            {
            background-color: #e74c3c;
        }

        }

        #btn10b,
        #btn10b {
            background-color: #e74c3c;
        },

        #btn10,
        #btn25b,
      
        #btn25b {
            background-color: #f1c40f;
        },
        #btn25,
        #btn50b,

        #btn50b {
            background-color: #2ecc71;
        }


        #btn50,
        #btn75b,
        
     
        #btn75b {
            background-color: #27ae60;
        }


        #btn75,
        #btn90b,

        #btn90b {
            background-color: #FF0000;
        }

     

        #btn90 {
            margin-right: 5px;
        }

        .fuente-bosst,
        .cruce-coseno {
            width: 50%;
            margin: 0 auto;
        }

        .fuente-bosst {
            text-align: left;
            float: left;
        }

        .cruce-coseno {
            text-align: right;
            float: right;
        }
    </style>
</head>

<body>
    <div class="fuente-bosst">
        <h3>Fuente Bosst</h3>
        <button class="button" id="btn10b" onclick="window.location.href='#10b'">10%</button>
        <button class="button" id="btn25b" onclick="window.location.href='#25b'">25%</button>
        <button class="button" id="btn50b" onclick="window.location.href='#50b'">50%</button>
        <button class="button" id="btn75b" onclick="window.location.href='#75b'">75%</button>
        <button class="button" id="btn90b" onclick="window.location.href='#90b'">90%</button>
        <button class="button" id="btnApagarb" onclick="window.location.href='#apagarb'">Apagar</button>
    </div>

    <div class="cruce-coseno">
        <h3>Cruce por coseno</h3>
        <button class="button" id="btn10" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagar" onclick="window.location.href='#apagar'">Apagar</button>
    </div>

</body>

</html>
