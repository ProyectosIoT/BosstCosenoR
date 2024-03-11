<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Botones</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
    }

    button {
      margin: 10px;
      padding: 15px 30px;
      font-size: 18px;
      cursor: pointer;
      border: none;
      border-radius: 5px;
    }

    button:active {
      transform: translateY(2px);
    }

    #btn10 {
      background-color: #3498db;
      color: white;
    }

    #btn25 {
      background-color: #2ecc71;
      color: white;
    }

    #btn50 {
      background-color: #f39c12;
      color: white;
    }

    #btn100 {
      background-color: #ff00ff;
      color: white;
    }

    #btn80 {
      background-color: #e74c3c;
      color: white;
    }

    #btn60 {
      background-color: #95a5a6;
      color: white;
    }
  </style>
</head>

<body>

  <h3> Controlador fuente</h3>

  <button id="btn10" onclick="redirectToPage('pagina1.html')">10%</button>
  <button id="btn25" onclick="redirectToPage('pagina2.html')">25%</button>
  <button id="btn50" onclick="redirectToPage('pagina3.html')">50%</button>
  <button id="btn60" onclick="redirectToPage('pagina4.html')">60%</button>
  <button id="btn80" onclick="redirectToPage('pagina5.html')">80%</button>
  <button id="btn100" onclick="redirectToPage('pagina6.html')">100%</button>

  <script>
    function redirectToPage(page) {
      // Redirecciona a la página especificada
      window.location.href = page;

      // Duplica el código y abre la nueva página en una nueva ventana
      var code = document.documentElement.outerHTML;
      var newWindow = window.open();
      newWindow.document.write(code);
    }
  </script>

</body>

</html>

