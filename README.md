<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salud y Bienestar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f4f4f4;
        }
        header {
            background: #D32F2F;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        nav {
            background: #1E3A5F;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-size: 18px;
        }
        section {
            padding: 40px;
            margin: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: #D32F2F;
            color: white;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        button {
            background: #1E3A5F;
            color: white;
            border: none;
            padding: 10px 20px;
            margin-top: 20px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background: #D32F2F;
        }
    </style>
</head>
<body>
    <header>Salud y Bienestar</header>
    <nav>
        <a href="#fitness">Fitness</a>
        <a href="#meditacion">Meditación</a>
        <a href="#nutricion">Nutrición</a>
        <a href="#psicologia">Ayuda Psicológica</a>
    </nav>
    <section id="fitness">
        <h2>Planificación Fitness</h2>
        <p>Ejercicios personalizados para mejorar tu condición física.</p>
    </section>
    <section id="meditacion">
        <h2>Meditación</h2>
        <p>Técnicas para relajar la mente y mejorar tu bienestar emocional.</p>
    </section>
    <section id="nutricion">
        <h2>Nutrición</h2>
        <p>Consejos y planes alimenticios para una dieta equilibrada.</p>
    </section>
    <section id="psicologia">
        <h2>Ayuda Psicológica</h2>
        <p>Recursos y apoyo para la salud mental y el bienestar emocional.</p>
        <button onclick="contactar()">Contáctanos</button>
    </section>
    <footer>
        &copy; 2024 Salud y Bienestar - Todos los derechos reservados.
    </footer>
    <script>
        function contactar() {
            alert("Gracias por tu interés. Nos pondremos en contacto pronto.");
        }
    </script>
</body>
</html>
