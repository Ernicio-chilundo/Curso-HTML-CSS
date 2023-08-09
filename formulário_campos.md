<DOCTYPE HTML>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport"
 content="width=device-width,
 initial-scale=1.0">
 <style>
  body{
   font-family:sans-serif;}
  label{
   cursor:pointer;}
 </style>
</head>
<body>
 <form action="#" method="get" target="_blank" autocomplete="off">
  <h2>O meu formulário</h2>
  <p>
   <label for="nome">Nome:</label><br>
   <input type="text" id="nome" name="nome"
   placeholder="Seu nome">
  </p>
  <p>
   <label for="dv1">Sou um dev 1:</label>
   <input type="checkbox" id="dv1" name="dev1" value="sim"><br>
  </p>
  <p>
   <label for="dev2">Sou um dev backend:</label>
   <input type="checkbox" id="dev2" name="dev2" value="sim"><br>

  </p>
   <label for="dev3">Sou um dev frontend:</label>
   <input type="checkbox" id="dev3" name="dev3" value="sim">
  <p>
   <button type="reset">Reset</button>
   <button type="submit">Enviar</button>
  </p>
</form>
</body>
</html>
