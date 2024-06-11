<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfil de GitHub</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
        }
        h1, h2 {
            color: #f0a500;
        }
        .section {
            margin-bottom: 30px;
            padding: 20px;
            border: 1px solid #f0a500;
            border-radius: 10px;
        }
        .section a {
            color: #f0a500;
            text-decoration: none;
            font-weight: bold;
        }
        .section a:hover {
            text-decoration: underline;
        }
        .stats img {
            max-width: 100%;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .header img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
        }
        .skill {
            background-color: #1e1e1e;
            border-radius: 5px;
            padding: 10px;
            margin: 5px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div>
            <h1>¡Hola! Soy [Tu Nombre]</h1>
            <p>Estudiante de programación de Barcelona</p>
        </div>
        <img src="https://avatars.githubusercontent.com/u/[tu-id-de-github]" alt="Mi Foto">
    </div>

    <div class="section">
        <h2>Sobre Mí</h2>
        <p>Hola, soy un apasionado de la programación con conocimientos en Java, Python, MySQL y PostgreSQL. Actualmente, estoy trabajando en un proyecto CRM que demuestra mis habilidades y compromiso con el desarrollo de software. Estoy buscando oportunidades para crecer profesionalmente y contribuir en proyectos innovadores.</p>
    </div>

    <div class="section">
        <h2>Proyecto Principal: CRM</h2>
        <p>Estoy desarrollando un sistema de CRM (Customer Relationship Management) que ayuda a las empresas a gestionar sus interacciones con los clientes y optimizar sus procesos de ventas.</p>
        <a href="https://github.com/tu-usuario/tu-proyecto">Ver Proyecto</a>
    </div>

    <div class="section">
        <h2>Habilidades</h2>
        <div class="skills">
            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">MySQL</div>
            <div class="skill">PostgreSQL</div>
        </div>
    </div>

    <div class="section stats">
        <h2>Estadísticas</h2>
        <p>Mis estadísticas de GitHub reflejan mi compromiso y actividad en la plataforma.</p>
        <img src="https://github-readme-stats.vercel.app/api?username=tu-usuario&show_icons=true&theme=dark" alt="Estadísticas de GitHub">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tu-usuario&layout=compact&theme=dark" alt="Lenguajes más utilizados">
    </div>
</body>
</html>
