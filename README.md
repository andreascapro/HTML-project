# HTML-project
<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina con Menù</title>
    <style>
        /* Stili di base */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Stile del menù */
        nav {
            background-color: #333;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav ul li {
            padding: 14px 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            display: block;
        }

        nav ul li a:hover {
            background-color: #575757;
        }

        /* Contenuto principale */
        main {
            padding: 20px;
        }
    </style>
</head>
<body>

    <!-- Menù di navigazione -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#servizi">Servizi</a></li>
            <li><a href="#chi-siamo">Chi Siamo</a></li>
            <li><a href="#contatti">Contatti</a></li>
        </ul>
    </nav>

    <!-- Contenuto principale -->
    <main>
        <h1>Benvenuto nel nostro sito!</h1>
        <p>Questa è una semplice pagina HTML5 con un menù di opzioni in alto.</p>
    </main>

</body>
</html>
