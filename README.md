<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
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

        #fuenteBosst {
            flex: 1;
        }

        #fuenteBosst .button {
            background-color: #e74c3c;
        }

        #cruceCoseno {
            flex: 1;
        }

        #cruceCoseno .button {
            background-color: #2ecc71;
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
        <button class="button" id="btn10" onclick="window.location.href='#10'">10%</button>
        <button class="button" id="btn25" onclick="window.location.href='#25'">25%</button>
        <button class="button" id="btn50" onclick="window.location.href='#50'">50%</button>
        <button class="button" id="btn75" onclick="window.location.href='#75'">75%</button>
        <button class="button" id="btn90" onclick="window.location.href='#90'">90%</button>
        <button class="button" id="btnApagar" onclick="window.location.href='#apagar'">Apagar</button>
    </div>
</body>

</html>
