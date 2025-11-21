# fernandotellezA.github.io
Portafolio fotográfico de Fernando Téllez — estilo editorial, blanco y negro, vintage y moda.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Fernando Téllez – Fotógrafo</title>

    <style>
        body {
            margin: 0;
            font-family: "Helvetica Neue", Arial, sans-serif;
            background-color: #f7f4ef;
            color: #222;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            background-color: #e9e4dd;
        }

        h1 {
            font-size: 48px;
            letter-spacing: 2px;
            color: #111;
        }

        h2 {
            text-align: center;
            margin-top: 60px;
            font-weight: 400;
            letter-spacing: 1px;
            color: #444;
        }

        p {
            max-width: 700px;
            margin: 20px auto;
            text-align: center;
            color: #333;
        }

        .gallery {
            max-width: 1100px;
            margin: 40px auto;
            display: grid;
            gap: 15px;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        }

        .gallery img {
            width: 100%;
            filter: grayscale(100%);
            border-radius: 6px;
        }

        footer {
            text-align: center;
            margin-top: 60px;
            padding: 30px;
            color: #555;
        }
    </style>
</head>

<body>
    <header>
        <h1>FERNANDO TÉLLEZ</h1>
        <p>Fotógrafo de moda • bodas • estética editorial vintage y B&W</p>
    </header>

    <h2>Sobre mí</h2>
    <p>
        Soy Fernando, fotógrafo colombiano con una mirada editorial que mezcla lo 
        clásico con lo íntimo. Trabajo en blanco y negro, tonos cálidos y una 
        estética que busca capturar el silencio, la emoción y la humanidad detrás 
        de cada imagen. Mi arte está inspirado en el renacer y la libertad.
    </p>

    <h2>Portafolio</h2>
    <div class="gallery">
        <img src="https://source.unsplash.com/featured/?fashion" alt="foto moda">
        <img src="https://source.unsplash.com/featured/?wedding" alt="foto boda">
        <img src="https://source.unsplash.com/featured/?editorial" alt="foto editorial">
        <img src="https://source.unsplash.com/featured/?portrait" alt="foto retrato">
    </div>

    <footer>
        © 2025 – Fernando Téllez • Portafolio Fotográfico
    </footer>
</body>
</html>
