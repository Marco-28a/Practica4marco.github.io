# Practica4marco.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background: #e8491d;
            color: #ffffff;
            padding: 10px 0;
        }
        nav ul {
            padding: 0;
            list-style: none;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #ffffff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px 0;
        }
        section {
            padding: 20px 0;
            background: #ffffff;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background: #35424a;
            color: #ffffff;
            text-align: center;
            padding: 20px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Logistica de Fletes</h1>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#acerca">Acerca de</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </div>
    </nav>

    <div class="container">
        <section id="inicio">
            <h2>Inicio</h2>
            <p>Esta es la sección de inicio de mi página web. Aquí puedes colocar una breve introducción.</p>
        </section>

        <section id="acerca">
            <h2>Acerca de</h2>
            <p>Información sobre ti, tu empresa o el propósito de esta página web.</p>
        </section>

        <section id="servicios">
            <h2>Servicios</h2>
            <p>Describe los servicios que ofreces o la informacián que quieres compartir.</p>
            <ul>
                <li>transporte de maquinaria</li>
                <li>transporte de alimentos</li>
                <li>coordinacion de rutas logisticas</li>
            </ul>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <p>Puedes incluir un formulario de contacto o tus datos de contacto aquó.</p>
            <form action="#" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required><br><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                
                <label for="mensaje">Mensaje:</label><br>
                <textarea id="mensaje" name="mensaje" rows="4" cols="50" required></textarea><br><br>
                
                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2023 Mi Página Web. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

