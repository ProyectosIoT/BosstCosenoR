<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: space-between;
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

        /* Estilos para la Fuente Bosst en el lado izquierdo */
        #fuenteBosst {
            text-align: center;
        }

        /* Estilos para el Cruce por coseno en el lado derecho */
        #cruceCoseno {
            text-align: center;
        }

        /* Colores modificados para el Cruce por coseno */
        #btn10Coseno {
            background-color: #e74c3c;
        }

        #btn25Coseno {
            background-color: #f1c40f;
        }

        #btn50Coseno {
            background-color: #2ecc71;
        }

        #btn75Coseno {
            background-color: #27ae60;
        }

        #btn90Coseno {
            background-color: #FF0000;
        }

        #btnApagarCoseno {
            background-color: #34495e;
        }
    </style>
</head>

<body>
    <div id="fuenteBosst">
        <h3>Fuente Bosst</h3>
        <button class="button" id="btn10" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagar" onclick="window.location.href='#apagar'">Apagar</button>
    </div>

    <div id="cruceCoseno">
        <h3>Cruce por coseno</h3>
        <button class="button" id="btn10Coseno" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25Coseno" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50Coseno" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75Coseno" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90Coseno" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagarCoseno" onclick="window.location.href='#apagar'">Apagar</button>
    </div>
</body>

</html>

