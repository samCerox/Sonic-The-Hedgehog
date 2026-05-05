<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sonic - Página Gamer</title>

    <style>
        body {
            margin: 0;
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #0d47a1;
            padding: 20px;
            text-align: center;
            box-shadow: 0 0 20px #2196f3;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
        }

        .container {
            padding: 30px;
            text-align: center;
        }

        .card {
            background-color: #111;
            border: 2px solid #0d47a1;
            border-radius: 15px;
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            box-shadow: 0 0 15px #0d47a1;
        }

        img {
            width: 250px;
            margin: 10px;
            transition: transform 0.3s;
        }

        img:hover {
            transform: scale(1.1);
        }

        h2 {
            color: #42a5f5;
        }

        footer {
            background-color: #0d47a1;
            text-align: center;
            padding: 10px;
            margin-top: 30px;
        }

    </style>
</head>

<body>

    <header>
        <h1>Sonic the Hedgehog</h1>
        <p>El erizo más rápido del mundo</p>
    </header>

    <div class="container">

        <div class="card">
            <h2>¿Quién es Sonic?</h2>
            <p>
                Sonic es un personaje icónico de los videojuegos creado por SEGA.
                Es famoso por su increíble velocidad, su actitud confiada y su lucha
                contra el villano Dr. Eggman.
            </p>
            <img src="https://upload.wikimedia.org/wikipedia/en/5/5c/Sonic_the_Hedgehog.png" alt="Sonic">
        </div>

        <div class="card">
            <h2>Personajes Principales</h2>

            <!-- Sonic -->
            <img src="https://upload.wikimedia.org/wikipedia/en/5/5c/Sonic_the_Hedgehog.png" alt="Sonic">

            <!-- Tails -->
            <img src="https://upload.wikimedia.org/wikipedia/en/e/e5/Tails2006.png" alt="Tails">

            <!-- Knuckles -->
            <img src="https://upload.wikimedia.org/wikipedia/en/9/9f/Knuckles_the_Echidna.png" alt="Knuckles">

        </div>

        <div class="card">
            <h2>Habilidades</h2>
            <p>
                Sonic puede correr a velocidades supersónicas, realizar saltos
                increíbles y derrotar enemigos en segundos. Su misión principal es
                detener los planes del Dr. Eggman y proteger el mundo.
            </p>
        </div>

        <div class="card">
            <h2>Sonic en Acción</h2>
            <img src="https://media.tenor.com/6eZ3G9J0J9gAAAAd/sonic-running.gif" alt="Sonic corriendo">
        </div>

    </div>

    <footer>
        <p>Proyecto HTML - Tema Sonic</p>
    </footer>

</body>
</html>
