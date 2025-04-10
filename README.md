<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=utf-8" />
    <title>Trabalho</title>
  
  </head>
  <body>
  
  </body>
</html>
<html lang="pt-br"> 
 <head>
   <header class="header" 
  <a href="/">logo</a>
   <nav>
     <u1 class="menu">
       <li> <a href="/">Sobre</a></li>
         <li> <a href="/">produtos</a></li
            <li> <a href="/">contato</a></li
     </u1>
   </nav>
  </header>
  
   <link rel= "stylesheet" href="Style.css">
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title> Trabalho</title> 
 </head>
 <body>
  <img src="https://i.imgur.com/q9wRYCE.jpeg" alt="dead cells"
  <h1>Olá, seja bem vindo ao meu trabalho</h1> 
  <p> Irei mostrar a você oque eu posso fazer com  trabalho, avalie e se gostar me contrate para fazer seu trabalho por um ótimo Preço.</p> 
  <p> Sou programador, design grafico e dev. Faço bots para discord e automação de mensagens.</p> 
  <p>Sou iniciante em python, java script, html, e css. mas como podem ver atravez desse site, eu já sei bastante coisa sobre. </p> 
  <h1>Faça seu login abaixo para confirmação.</h1>
  <script src="Script.js"></script>
   
   
   <div class="main-login">
        <div class="left-login"
            <h1> Faça login<br>aqui</h1>
      </div>
     <div class="right-login">
        <div class="card-login">
          <h1>Login</h1>
          <div class="textfield">
            <label for="usuario">Usuario</label>
              <input type="text" name="Usuario" placeholder="Usuario">
          </div>
          <div class="textfield">
             <label for="senha">senha</label>
                <input type="password""senha" placeholder="senha"
                 
          </div>
          <button class="btn-login">login</button>
     
    
 </body>
</html

@import url('https://fonts.googleapis.com/css2?family=Noto+Sans:ital,wght@0,100..900;1,100..900&display=swap');

body{
  background-color: #FFFFFF;
  margin: 0;
  font-family: 'noto Sans', sans serif;
}

.main-login{
  width: 100vw;
  height: 100vh;
  background:#FFFFFF;
  display: flex;
  justify-content: center;
  align-items: center;
}
.left-login{
  width: 50vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
.left-login > h1 {
  color: #13E089;
  font-size: 3vw;
}
.right-login {
  width:50vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  
}

.card-login{
  width: 60%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 30px 35px;
  background: #5D52AF;
  border-radius: 20px;
  box-shadow: 0px 10px 40px #2B2828;
  position: relative;
  top: -70px;
  
}

.card-login > h1 {
  color: #2EF49E;
  font-weight: 800;
  margin: 0 ;
}
.textfield {
  width: 100%;
  display: flex;
  flex-direction:column;
  align-items: flex-start;
  justify-content: center;
  margin: 10px 0px;
}

.textfield > input {
  width: 100%;
  border: none;
  border-radius: 10px;
  padding: 15px;
  background: #444E7D;
  color: #4DFF7E;
  font-size: 12pt;
  box-shadow: 0px 10px 40px;
  outline: none;
  box-sizing: border-box
  
}

.textfield > label {
  color: #2C2A2A;
  margin-bottom: 10px;
  
}

.textfield > input::placeholder {
  color: #5BBDC8;
  
}

.btn-login {
  width: 100%;
  padding: 16px 0px;
  margin: 25px;
  border: none;
  border-radius: 8px;
  outline: none;
  font-weight: 800;
  letter-spacing: 3px;
  color: #1A1C1B;
  background: #16E9A5;
  cursor: pointer;
  box-shadow: 0px 10px 40px #2C6754;
  
  
}

@media only screen and (max-width: 950px){
  .card-login{
    width: 85%;
  }
}

@media only screen and (max-width: 600px){

  }  
  
  .left-login > h1 {
    font-size: 40px;
    
  }
  

p{
  font-size: 20px;
position: relative;
left: 10px;
}

h1{
  color: #0F9DDA;
  text-align: center;
  position: relative;
  left: 10px;
}

img{
  width: 200px;
  height:200px;
  object-fit: cover;
  border-radius: 50%;
  display: block;
  margin: 0 auto;
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 50%;
  margin-top: 30px;
  
}
body, u1, li, p {
  margin: 0;
  padding:  0px;
  list-style: none;
  font-size: 1.2rem;
  font-family: Arial;
}

a{
  text-decoration: none;
  color: #FFFFFF;
  
}
.header{
  background: #000000;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 20px;
  align-items: center;
  
  
}

.menu{
  display: flex;
  
}

.menu li{
  margin-left: 10px;
}

.menu li a{
  display: block;
  padding: 10px;
  background: #117E9E;
  
}



    
