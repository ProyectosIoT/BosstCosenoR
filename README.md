# FuenteBosstR
<html lang="en">

  
  
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
    #btnOn {
      background-color: #e74c3c;
      color: white;
    }

    #btnOff {
      background-color: #95a5a6;
      color: white;
    }
  </style>


<h3> Controlador led 
 
 <button id="btn10">10%</button>
    <button id="btn25">25%</button>
    <button id="btn50">50%</button>
    <button id="btn100">100%</button>
  
 <h3> Motor   
 
   <button id="btnOn">Prender</button>
     <button id="btnOff">Apagar</button>
  
  
