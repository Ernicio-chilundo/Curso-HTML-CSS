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
   <label for="dev2">Sou um dev backend:</label>
   <input type="checkbox" id="dev2" name="dev2" value="sim"><br>
   <label for="dev3">Sou um dev frontend:</label>
   <input type="checkbox" id="dev3" name="dev3" value="sim">
  </p>
  <p>
  GENERO:<br>
   <label for="feminino">Feminino:</label>
   <input type="radio" id="feminino" name"genero" value="feminino"><br>
   <label for="masculino">Masculino:</label>
   <input type="radio" id="masculino" name="genero" value="masculino"><br>
   <label for="outro_outra">Outro ou Outra:</label>
   <input type="radio" id="outro_outra" name="genero" value="outro_oitra">
  </p>
  <p>
   <label for="date">Date:</label>
   <input type="date" id="date" name="date" value="2024-07-25">
  </p>
  <p>
   <label for="datetime">Date:</label>
   <input type="datetime" id="datetime" name="datetime" value="2024-07-25T18:36">
  </p>
  <p>
   <label for="time">Time:</label>
   <input type="time" id="time" name="time"
 value="12:53:47">
  </p>
   <label for="cor">Cor Preferida</label>
   <input type="color" id="cor" name="cor" value="#FFFF00">
  <p>
   <button type="reset">Reset</button>
   <button type="submit">Enviar</button>
  </p>
</form>
</body>
</html>
