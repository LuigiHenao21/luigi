# luigi
san valentin
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Serás mi San Valentín?</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <audio id="music" autoplay loop>
        <source src="tu-cancion.mp3" type="audio/mpeg">
        Tu navegador no soporta audio.
    </audio>

    <div class="container">
        <h1>💖 Hola, mi amor 💖</h1>
        <p>He preparado esto para preguntarte algo muy especial...</p>
        
        <div class="photo-frame">
            <img src="tu-foto.jpg" alt="Nosotros">
        </div>

        <p class="question">¿Quieres ser mi San Valentín? 💘</p>

        <div class="buttons">
            <button id="yes-btn">¡Sí, obvio! 💕</button>
            <button id="no-btn">No... ❌</button>
        </div>
        
        <p id="response"></p>
        
        <button id="music-btn">🎵 Pausar música</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
