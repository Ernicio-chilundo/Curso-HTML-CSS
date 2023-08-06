<DOCTYPE HTML>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport"
 content="width=device-width,
 initial-scale=1.0">
 <title>Document</title>
 <style>
  body{
   font-family:sans-serif;}
  table{
   border-collapse:collapse;
   width:1000px;}
  table td ,table th{
   border:1px solid #ccc;
   padding:5px;
   text-align:left;}
   tfoot td ,table th{
    background:#ddd;}
   tfoot td{
    font-style:italic;}
   table caption{
    caption-side:bottom;
    text-align:right;
    font-style:italic;
    font-size:12px;
    margin:5px 0;}
   .responsive-table{
    max-width:100%;
    overflow-x:auto;}
 </style>
</head>
<body>
 <p>Good morning ...</p>
 <div class="responsive-table">
  <table>
   <caption>TABELA FORMADA COM SUCESSO</caption>
   <thead>
    <tr>
     <th>ERNICIO 1</th>
     <th>ERNICIO 2</th>
     <th>ERNICIO 3</th>
    </tr>
   </thead>
   <tbody>
    <tr>
     <td>CORPO 1</td>
     <td>CORPO 2</td>
     <td>CORPO 3</td>
    </tr>
    <tr>
     <td colspan="2">GOOD</td>
     <td>CORPO 3</td>
    </tr>
    <tr>
     <td>CORPO 1</td>
     <td>CORPO 2</td>
     <td>CORPO 3</td>
    </tr>
   </tbody>
   <tfoot>
    <tr>
     <td colspan="2" rowspan="2"></td>
     <td>TOTAL:</td>
    </tr>
    <tr>
     <td>R$2023</td>
    </tr>
   </tfoot>
  </table>
 </div>
</body>
</html>
