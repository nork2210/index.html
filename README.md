meu portafolio 

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">
<link rel="stylesheet" href="style.css">
<title>MY PORTAFOLIO</title>
</head>
<body>

<div class="background">
<header>

<div class="encabezado-link">
<li><a href="#">Home</a></li>
<li><a href="#">Formacão</a></li>
<li><a href="#">Experiência profissional</a></li>
<button>Download CV</button>
</div><!--insertar encabezado-->
<div class="redes-sociales">
<a href="#"><i class="fa-brands fa-facebook"></i></a>
<a href="#"><i class="fa-brands fa-instagram"></i></a>
<a href="#"><i class="fa-brands fa-youtube"></i></a>
<a href="#"><i class="fa-brands fa-twitter"></i></a>
</div><!--redes sociales-->

</header>

<div class="container-text">
<div class="text">
<h3> Ola acredito que, antes de ser um bom profissional, seja um bom ser humano.
    
    
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100&family=Roboto+Mono:ital,wght@1,500&display=swap');
*{
margin: 0;
padding: 0;
box-sizing: border-box;
text-decoration: none;
list-style: none;
font-family: 'Roboto Mono', monospace;
}

body{
overflow: hidden;
}

.background{
background: linear-gradient (rbga(0, 0, 0, 0.5), rbga(0, 0, 0, 0,5));
background-image: url(foto22.jpg);
background-size: cover;
background-position: center;
background-repeat: repeat;
width: 100%;
height: 100vh;
}

header{
display: flex;
justify-content: space-around;
max-width: 100%;
align-items: center;
text-align: center;
padding-top: 1rem;
}
.encabezado-link{
display: flex;
gap: 3rem;
font-weight: 500;
cursor: pointer;
}
.encabezado-link a{
color: blue;
font-size: 12;
}
.encabezado-link a:hover{
color: #cc2e63;
transition: 0.3s all;
}

button{
color: #e40909;
background: right center;
border: solid 1px #8fd8d8;
padding: 5px;
border-radius: 15px;
font-size: 15px;
width: 150px;
cursor: pointer;
}

button:hover{
background-color: #9c9292;
color: blue;
transition: 0.5s;

}
.container-text{
padding: 150px 0 0 130px;

}

.text h3{
color: black;
font-size: 15px;
}

.text h1{
color: black;
margin-top: 10px;
}

.text span{
color: #0c0d0e;
}

.text p{
color: rgb(40, 22, 197);
font-size: 10px;
font-weight: 10px;

background-image: url(foto.jpg);
border: 1px solid #ddd;
padding: 10px; 
margin: 10px; 
border: 2px solid black; 
border-bottom-right-radius: 50% 50%;
float: left; 
width: 210px; 
height: 25vh;
}
.redes-sociales a{
color: red;
min-height: 100vh;
display:contents;
justify-content: flex-end;
align-items: flex-end;
}

.btn{
margin-top: 300px;
background-size: 65px 65px;
border-radius: 60%;
background-size: 20px;
background-position: center center;
}


    
    Não importa sim é lento ou rápido.
    O que importa é evoluir.</h3>

<h1>Eu sou<span> Norkis Reyes.</span></h1>


<p> ING. DE PETROLEO  E   ESTUDANTE  DA TOTI </p>.

</div><!--text-->


<button class="btn">Ir a Portafolio</button><br>
</div><!--container text-->


</div><!-- vamos a trabalhar a parte de background-->
</body>
</html>
