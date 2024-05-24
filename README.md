(site1)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login</title>
<link rel="stylesheet" href="site.css">

</head>
<body>
    <section class="area-login">
        <div class="login">
            <div>
                <img src="puma.png" alt="">
            </div>
<form>
    <input required type="text" name="nome" placeholder="nome de usuario">
    <input required type="text" name="senha" placeholder="sua senha">
    <input  type="submit" value="entrar">

</form>
<p>ainda nao tem uma conta?<a href="">criar conta!</a></p>
        </div>
    </section>
    
</body>
</html>
(css)
body{
background-color: #1B1F27;
font-family: Arial, Helvetica, sans-serif;
overflow: hidden;
}
.area-login{
    height: 100vh;
    display: flex;
justify-content: center;
align-items: center;
}
.login{
    background-color: #181920;
    width: 350px;
    height: 300px;
}
.login form{
    display: flex;
    flex-direction: column;
}
.login input{
    margin-top: 10px;
    background-color: #181920;
}
.login img{
    background-color: #181920;
    justify-content: center;
    align-items: center;
    width: 350px;
}
input::placeholder{
    color: aqua;
    font size: 14px;
    
}
input[type="submit"] {
    display: block;
    background-color: blueviolet;
    font-size: 14px;
}
.senha{
    background-color: blue;
    border: brown 20px solid;
}

(site2)
!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>site</title>
    <link rel="stylesheet" href="site2.css">
</head>
<body>
    <div class="container">
    <form action="site2.php">
    <h1><ul>Faça login para prosseguir</ul></h1>
    <img src="unnamed.png" alt="">
    
    <br><input class="nome" type="text" nome="usuario" placeholder="Nome do usuario">
    <label for="usuario"></label>
    <br><input  class="senha" type="password" nome="senha" placeholder="sua senha">
   <br><input type="checkbox" name="" id="" value="nao sou um robo!">Nao sou um robo
    <br> <input class="submit" type="submit" value="cadastrar-se">
   <input class="submit"  type="submit" value="esqueceu sua senha?">
    <p>nao possui uma conta? <a href="">criar conta</a></p>
    </form>
</div>


    
</body>
</html>
(css2)
body{
    align-content: center;
    justify-content: center; 
}
.nome{
    
    background-color: gray ;
    border: solid red;
}

input[type="submit"] {
    display: block;
    background-color: blueviolet;
    font-size: 14px;
    
}
img{
    width: 100px;
    height: 100px;
    border: solid 2px orange;
    display: block;
    margin: 0 auto;

}
.senha{
    background-color: blue;
    border: brown solid;
   
}
input::placeholder{
    color: aqua;
    font size: 14px;
    
}
 

form {
    text-align: center;
}
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Isso centralizará verticalmente na página inteira */
}

.submit{ 
    justify-content: center;
    align-items: center;
    margin: auto; /* Centraliza horizontalmente os botões */
    display: block; /* Garante que os botões ocupem toda a largura disponível */
    width: fit-content; /* Define a largura do botão baseada no conteúdo */
}
form{
    display: flex;
    flex-direction: column;
}








