<!DOCTYPE html>
<html>
<head>
   <link rel="stylesheet" type="text/css" href="style.css">
   <title></title>
</head>
<body>
   <h1>FORMULÁRIO DE CADASTRO</h1>
   <main>
       <form>
           <label for="nome">NOME</label>
           <input type="text" id="nome" required>
           <label for="end_email">EMAIL</label>
           <input type="email" id="end_email" required>    
           <label for="tfone">TELEFONE</label>
           <input type="tel" id="tfone" required>   
           <div>
               <p>Desejar receber notícias?</p><input type="radio" >
               <br>

               <p>Marque aqui</p><input type="checkbox">
               <br>

               <input type="submit" value="ENVIAR">
           </div>

           <div>
               <textarea cols="70" rows="15" required></textarea>
           </div>
       </form>
   </main>
</body>
</html>
