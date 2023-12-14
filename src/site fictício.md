### Cod html

<! <!DOCTYPE html>

-<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./../css/home.css">
    <title>Document</title>
</head>


<body>
    <header>
        <h1>Menu de Navegação - Exercicio 1</h1>
        <nav>
            <ul>
                <li><a href="exercicio1.html">Home</a></li>
                <li><a href="exercicio2.html">Sobre</a></li>
                <li><a href="exercicio3.html">Serviços</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
       <td>
        <tr>
            <h1>Bem-vindo ao Meu site</h1>
        </tr>
       </td>
    
        <p>Este é um site fictício com um menu de interação simples</p>
    
    </main>

</body>
</html> ->

### Cod css

body {

  font-family: Arial, sans-serif;

  margin: 0;

  padding: 0;

  background-color: #f4f4f4;

}

header {

  background-color: #333333;

  color: #fff;

  padding: 10px;

  text-align: center;

}

nav {

  background-color: rgb(0, 225, 255);

  padding: 10px;

  text-align: center;

}

nav ul {

  list-style: none;

  margin: 0;

  padding: 0;

}

nav li {

  display: inline;

  margin-right: 10px;

}

nav a {

  text-decoration: none;

  color: #fff;

  padding: 8px 15px;

  border-radius: 0px;

  transition: background-color 0.3s ease;

}

nav a:hover {

  background-color: #444;

}

main{

  text-align: center;

}