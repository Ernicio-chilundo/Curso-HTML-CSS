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
   <label for="datetime">Datetime:</label>
   <input type="datetime-local" id="datetime" name="datetime" value="2024-07-25T18:36">
  </p>
  <p>
   <label for="time">Time:</label>
   <input type="time" id="time" name="time"
 value="12:53:47">
  </p>
   <label for="cor">Cor Preferida</label>
   <input type="color" id="cor" name="cor" value="#FFFF00">
  <p>
   <label for="email">Email:</label>
   <input type="email" id="email" name="email" placeholder="ex:.email@email.com">
  </p>
  <p>
   <label for="password">Password:</label>
   <input type="password" id="password" name="password" placeholder="Sua senha">
  </p>
  <p>
   <label for="file">Sua foto:</label>
   <input type="file" id="file" name="file" value=".png,.svg.image/*" multiple>
  </p>
  <p>
   <label for="number">Number:</label>
   <input type="number" id="number" name="number" placeholder="Digite um numero">
  </p>
  <p>
   <label for="range">Range:</label>
   <input type="range" id="range" name="range" min="0" max="10" step="5">
  </p>
  <p>
   <label for="url">URL:</label>
   <input type="url" id="url" name="url" placeholder="URL">
  </p>
  <p>
   <label for="search">Search</label>
   <input type="search" id="search" name="search" placeholder="Sua url">
  </p>
  <p>
   <label for="select">Selecione uma opção:<label>
   <select id="select" name="select">
    <option value="qualquer 1" disabled>Valor 1</option>
    <option value="qualquer 2">Valor 2</option>
    <option value="qualquer 3">Valor 3</option>
    <option value="qualquer 4" selected>Valor 4</option>
   </select>
  </p>
  <p>
   <label for="textarea">TextArea:</label>
   <textarea id="textarea" name="textarea" rows="10">
   </textarea>
  </p>
  <p>
   <button type="reset">Reset</button>
   <button type="submit">Enviar</button>
  </p>
</form>
</body>
</html>
