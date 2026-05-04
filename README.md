<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AMARTÍZ — Inicio</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Lato:wght@400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --cafe-oscuro: #3B1F0E;
            --dorado: #C9973A;
            --bg-crema: #F5EDE0;
        }

        body {
            font-family: 'Lato', sans-serif;
            background-color: var(--bg-crema);
            color: var(--cafe-oscuro);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            text-align: center;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        p {
            margin-bottom: 40px;
            font-style: italic;
            opacity: 0.8;
        }

        .menu-container {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            text-decoration: none;
            color: var(--cafe-oscuro);
            width: 250px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s, border 0.3s;
            border: 2px solid transparent;
        }

        .card:hover {
            transform: translateY(-10px);
            border-color: var(--dorado);
        }

        .card h2 {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        .card span {
            font-size: 0.9rem;
            line-height: 1.4;
            display: block;
        }

        .badge {
            background: var(--dorado);
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.7rem;
            font-weight: bold;
            text-transform: uppercase;
            margin-bottom: 10px;
            display: inline-block;
        }
    </style>
</head>
<body>

    <h1>AMARTÍZ</h1>
    <p>Arte y tradición en cada fibra</p>

    <div class="menu-container">
        <!-- Enlace a tu primera página -->
        <a href="Poshoo.html" class="card">
            <div class="badge">Catálogo</div>
            <h2>Colecciones</h2>
            <span>Explora nuestros huipiles y usa el probador virtual.</span>
        </a>

        <!-- Enlace a tu segunda página -->
        <a href="amartiz-craft.html" class="card">
            <div class="badge">Tradición</div>
            <h2>Proceso Artesanal</h2>
            <span>Conoce el origen de la lana y el arte del telar de cintura.</span>
        </a>
    </div>

    <footer style="margin-top: 50px; font-size: 0.8rem; opacity: 0.6;">
        © 2026 Proyecto Universitario — AMARTÍZ
    </footer>

</body>
</html>
