<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: space-between;
            text-align: center;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            font-size: 18px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s;
        }

        .button:hover {
            background-color: #3498db;
        }

        .button:active {
            transform: translateY(2px);
        }

        #btn10,
        #btn25,
        #btn50,
        #btn75,
        #btn90,
        #btnApagar {
            color: white;
        }

        /* Colores para la sección de Fuente Bosst */
        #btn10,
        #btn25,
        #btn50,
        #btn75,
        #btn90,
        #btnApagar {
            background-color: #e74c3c;
        }

        /* Colores modificados para la sección de Cruce por coseno */
        #btn10_coseno,
        #btn25_coseno,
        #btn50_coseno,
        #btn75_coseno,
        #btn90_coseno,
        #btnApagar_coseno {
            background-color: #3498db;
        }
    </style>
</head>

<body>
    <div>
        <h3>Fuente Bosst</h3>
        <button class="button" id="btn10" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagar" onclick="window.location.href='#apagar'">Apagar</button>
    </div>

    <div>
        <h3>Cruce por coseno</h3>
        <button class="button" id="btn10_coseno" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25_coseno" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50_coseno" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75_coseno" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90_coseno" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagar_coseno" onclick="window.location.href='#apagar'">Apagar</button>
    </div>
</body>

</html>

