# Project_HTML
Alguns Projetos meu em HTML E CSS
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IMC</title>
  <style>
  html{
    background-color: #000000;
  }
  main{
  margin: auto;
  display: flex;
  justify-content: center;
 
 
  background-color: #000000;
  

  }
  button{
  width: 300px;
  height: 40px;
  font: bold 1.2rem serif;
  background: #000;
  color: rgb(255, 255, 255);
  outline: none;
  border-radius: 5px;
  cursor: pointer;
  box-shadow: 0px 0px 10px #FFF;
  }
  footer{
    box-shadow: 0px 0px 10px #ffffff;
  width: auto;
 
  display: flex;
  justify-content: space-evenly;
  background-color: #000000;
  color: #FFF;
  }
  footer div{

  display: contents;
  box-shadow: #FFF;
  }
  body{
    background-color: #f5f4f4;
  }
  .space{
  display: flex;
  justify-content: space-around;
  background-color: #000000;
  width: auto;
  height: 600px;

  } 
 img{
  background-color: #FFF;
  border-radius: 8%;
  height: 300px;
  position: absolute;
  top: 28%;
  left: 18%;
  
  }
  header{
    display: flex;
    justify-content: flex-end;
    height: 60px;
    background-color: #000000;


  }
  header button{
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: #FFF;
    color: #000;
    position: absolute;
    left: 95%;
  }

  .container{
  display: flex;
  flex-direction: column;
  background: rgb(63, 63, 63);
  width: 500px;
  height: 500px;
  align-items: center;
  justify-content: space-evenly;
  border-radius: 20px;
  box-shadow: 0px 0px 10px #ffffff;
  margin: 5%;
  margin-left: 40%;
  }

  .title{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 50px;
  font: bold 2.5rem serif;
  border-bottom: solid 5px black;
  margin-bottom: 20px;
  }

  .input {
  display: flex;
  width: 300px;
  height: 50px;
  justify-content: space-between;
  align-items: center;
  }
  .input input {
  width: 200px;
  height: 50px;
  border-radius: 5px;
  border:none;
  outline: 0;
  font: bold 1.5rem serif;
  text-align: center;

  }

  .input label {
  font: bold 1.5rem serif;

  }

 
  .result{
  box-shadow: 0px 0px 10px #FFF;
  width: 600px;
  height: 198px;
  border-radius: 5px;
  display: flex;
  margin-top: 20px;
  align-items: center;
  font: italic 1.5rem serif;
  margin: 1%;
  background: #000;
  color: rgb(0, 225, 255);
  padding: 20px;
  box-sizing: border-box;
  user-select: none;

  }


  </style>
</head>
<header>
    <button>?</button>
  
  </header>
<body>
  
    <img src="images.png" alt="triangulo">
  <div class="space">
    
    <div class="container">
      <div class="title">Calculadora de Ângulos</div>
      <div class="input">
    
          <label>Lado a:</label>
          <input type="text" id='nome'>
      </div>
      <div class="input">
          <label>Lado b:</label>
          <input type="number" id='altura'>
      </div>
      <div class="input">
          <label>Lado c:</label>
          <input type="number" id='peso'>
      </div>
      <div class="input">
        <label>Lado α:</label>
        <input type="number" id='peso'>
    </div>
    <div class="input">
      <label>Lado β:</label>
      <input type="number" id='peso'>
        </div>
      <button id='calcular'>Calcular</button>
    </div>
  </div>

  <div>
  <main>
  <div class="result">

  </div>
</div>
</main>

<footer >
  
      
        
  <div>
    <p><b>Alunos: Lucaz Liz  | Luiz Guilherme </b></p>
    
    <p><b>RGA:xxxxxxxxxxx | RGA:202319070351</b></p>
  </div>
  
</footer>
<script src="js/imc.js"></script>
  </body>
</html>
