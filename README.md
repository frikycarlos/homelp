
<!doctype html>
<html lang="es">
<head>
    <title> PRACTICA </title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            margin: 0;
        }
        .header {
            background-color: #f1f1f1;
            padding: 20px;
            text-align: center;
               }
        .menu {
            overflow: hidden;
            background-color: #333;
                }

        .menu a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }


        .menu a  {
            background-color: #ddd;
            color: black;
        }

        .columna {
            float: left;
            width: 33.33%;
            padding: 15px;
        }
        .fila:after {
            content: "";
            display: table;
            clear: both;
        }


        .cuadrado {
            background-color: tomato;
            width: 400px;
            height: 400px;
            line-height: 400px;
            text-align: center;
        }

        .columna.aside {
            width: 25%;
        }
        .footer {
            background-color: #f1f1f1;
            padding: 10px;
            text-align: center;
        }

    </style>
</head>
<body>

<div class="header">
    <h1>PAGINA WEB</h1>
</div>
<div class="menu">
    <a href="#">Link</a>
    <a href="#">Link</a>
    <a href="#">Link</a>
</div>
<div class="fila">
    <div class="columna">
        <h2>Columna</h2>
        <article class="cuadrado">CARLOS EMMANUEL RANGEL ACOSTA</article>
    </div>
</div>
<div class="fila">
<div class="columna aside">
    <h2>Side</h2>

</div>
</div>
</div>

<div class="footer">
    <p>Footer</p>
</div>

</body>
















</html>
