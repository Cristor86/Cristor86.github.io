# Cristor86.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Ciberseguridad - Cristo Ribas Hernández</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #1a1a2e;
            color: white;
            text-align: center;
            padding: 2em;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            font-size: 1.2em;
        }
        nav {
            background-color: #16213e;
            padding: 1em;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1em;
            font-size: 1.1em;
        }
        nav a:hover {
            color: #00d4ff;
        }
        .container {
            max-width: 1000px;
            margin: 2em auto;
            padding: 0 1em;
        }
        .section {
            background-color: white;
            padding: 2em;
            margin-bottom: 2em;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .section h2 {
            color: #1a1a2e;
            border-bottom: 2px solid #00d4ff;
            padding-bottom: 0.5em;
        }
        .project {
            margin-bottom: 1.5em;
        }
        .project h3 {
            color: #16213e;
        }
        .project p {
            line-height: 1.6;
        }
        footer {
            background-color: #1a1a2e;
            color: white;
            text-align: center;
            padding: 1em;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer a {
            color: #00d4ff;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8em;
            }
            nav a {
                display: block;
                margin: 0.5em 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Cristo Ribas Hernández</h1>
        <p>Estudiante de Ciberseguridad | Google Coursera</p>
    </header>
    <nav>
        <a href="#about">Sobre Mí</a>
        <a href="#projects">Proyectos</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <div class="section" id="about">
            <h2>Sobre Mí</h2>
            <p>Soy un estudiante apasionado de ciberseguridad, actualmente formándome a través del programa de Google Coursera. Mis áreas de interés incluyen la detección de amenazas, la gestión de incidentes y la configuración segura de sistemas. Estoy comprometido con aprender y aplicar las mejores prácticas para proteger la información y los sistemas.</p>
            <p><strong>Habilidades:</strong> Análisis de logs, fundamentos de redes, configuración de firewalls, respuesta a incidentes, Linux, Python (básico).</p>
        </div>
        <div class="section" id="projects">
            <h2>Proyectos</h2>
            <div class="project">
                <h3>Análisis de Logs de Seguridad</h3>
                <p>Realicé un análisis de logs de un sistema para identificar intentos de acceso no autorizados utilizando herramientas como Splunk. Documenté los hallazgos y propuse medidas de mitigación.</p>
            </div>
            <div class="project">
                <h3>Configuración de un Firewall</h3>
                <p>Configuré un firewall en un entorno simulado utilizando pfSense para proteger una red interna. Implementé reglas para bloquear tráfico malicioso y permitir servicios esenciales.</p>
            </div>
            <div class="project">
                <h3>Simulación de Phishing</h3>
                <p>Diseñé una campaña de phishing simulada para educar a usuarios sobre cómo identificar correos maliciosos. Analicé las respuestas y presenté un informe con recomendaciones de seguridad.</p>
            </div>
        </div>
        <div class="section" id="contact">
            <h2>Contacto</h2>
            <p>Conéctate conmigo:</p>
            <p>
                <a href="https://www.linkedin.com/in/cristo-ribas-hern%C3%A1ndez-633737276/" target="_blank">LinkedIn</a> | 
                <a href="https://github.com/Cristor86" target="_blank">GitHub</a> | 
                Email: <a href="mailto:cristoribas86@gmail.com">cristoribas86@gmail.com</a>
            </p>
        </div>
    </div>
    <footer>
        <p>© 2025 Cristo Ribas Hernández. Todos los derechos reservados.</p>
    </footer>
</body>
