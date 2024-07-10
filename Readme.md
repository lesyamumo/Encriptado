<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Encriptador AES</title>
<link rel="stylesheet" href="styles.css">
</head>
<body class="body">
  <div class="container">
    <h1>Encriptador AES</h1>
    <textarea id="inputText" placeholder="Introduce el texto a encriptar/desencriptar"></textarea>
    <div class="buttons">
      <button onclick="encryptText()">Encriptar</button>
      <button onclick="decryptText()">Desencriptar</button>
    </div>
    <textarea id="outputText" placeholder="Texto encriptado/desencriptado aparecerá aquí"></textarea>
  </div>
  <script src="script.js"></script>
</body>
</html> 
