<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D&F Precisión</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-image: url('https://drive.google.com/uc?export=view&id=1TH70Y8t1fN8W5j2PC2eG-cLl2XGOruDx'); /* ¡Enlace directo de tu imagen! */
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 48px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente para mejor legibilidad */
            display: inline-block;
            padding: 10px 20px;
            border-radius: 5px;
        }
        section {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            padding: 20px;
            max-width: 1000px;
            animation: fadeIn 0.5s ease-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border: 2px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        form {
            max-width: 400px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }
        input, textarea, button {
            margin: 5px 0;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #218838;
        }
        .justificado {
            text-align: left;
            max-width: 800px;
            margin: auto;
        }
        .mision-vision {
            display: flex;
            justify-content: center;
            gap: 20px;
            max-width: 900px;
            margin: auto;
        }
        @media (max-width: 600px) {
            .mision-vision {
                flex-direction: column;
            }
            .mision-vision div {
                width: 100%;
            }
        }
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer a {
            color: #28a745;
            margin: 0 10px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>D&F Precisión</h1>
    </header>
    <main>
        <section>
            <h2>Sobre Nosotros</h2>
            <p class="justificado">En D&F Precisión, nos especializamos en el diseño y fabricación de piezas mecánicas de alta precisión. 
               Brindamos servicios de mecanizado, prototipado y producción en serie, asegurando calidad en cada detalle. 
               Nuestro equipo combina experiencia y tecnología para transformar tus ideas en productos funcionales con acabados impecables.</p>
        </section>
        <section>
            <h2>Servicios</h2>
            <div style="display: flex; justify-content: space-around; flex-wrap: wrap;">
                <div style="text-align: center; width: 200px; margin: 10px;">
                    <img src="https://via.placeholder.com/50" alt="Torneado">
                    <p>Torneado y fresado de precisión</p>
                </div>
                <div style="text-align: center; width: 200px; margin: 10px;">
                    <img src="https://via.placeholder.com/50" alt="Diseño">
                    <p>Diseño y fabricación de piezas mecánicas</p>
                </div>
                <div style="text-align: center; width: 200px; margin: 10px;">
                    <img src="https://via.placeholder.com/50" alt="Prototipado">
                    <p>Prototipado y producción en serie</p>
                </div>
                <div style="text-align: center; width: 200px; margin: 10px;">
                    <img src="https://via.placeholder.com/50" alt="Ingeniería">
                    <p>Ingeniería inversa y optimización de componentes</p>
                </div>
            </div>
            <a href="#cotizacion" style="text-decoration: none;">
                <button style="margin-top: 20px;">Solicitar Cotización</button>
            </a>
        </section>
        <section class="mision-vision">
            <div>
                <h2>Misión</h2>
                <p>En D&F Precisión, nos dedicamos a transformar la industria del mecanizado a través de un servicio de excelencia. 
                   Nuestra misión es ofrecer soluciones innovadoras en diseño y fabricación, con un alto nivel de precisión y eficiencia. 
                   Nos diferenciamos por nuestro nivel de respuesta, compromiso con la calidad y enfoque en la optimización de procesos para nuestros clientes, 
                   contribuyendo así a su competitividad en el mercado.</p>
            </div>
            <div>
                <h2>Visión</h2>
                <p>Ser líderes en la industria del mecanizado, reconocidos por nuestro nivel de servicio, precisión y capacidad de innovación. 
                   Buscamos posicionarnos como la mejor opción para empresas que requieren soluciones eficientes y de alta calidad, 
                   destacándonos en un mercado cada vez más competitivo.</p>
            </div>
        </section>
        <section>
            <h2>Galería</h2>
            <div class="gallery">
                <img src="https://via.placeholder.com/300" alt="Plano de fabricación">
                <img src="https://via.placeholder.com/300" alt="Programa de diseño">
                <img src="maquina-torno.jpg" alt="Máquina de torno en acción">
                <img src="pieza-terminada.jpg" alt="Pieza terminada con acabado de precisión">
            </div>
        </section>
        <section id="cotizacion">
            <h2>Solicita una Cotización</h2>
            <form action="https://formspree.io/f/myyabcde" method="POST">
                <input type="text" name="nombre" placeholder="Nombre" required>
                <input type="email" name="correo" placeholder="Correo" required>
                <textarea name="mensaje" placeholder="Descripción del trabajo" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section>
            <h2>Ubicación</h2>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12345.6789!2d-99.123456!3d19.123456!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMTnCsDA3JzI0LjgiTiA5OcKwMDcnMjQuOCJX!5e0!3m2!1ses!2smx!4v1234567890123!5m2!1ses!2smx" 
                    width="100%" 
                    height="300" 
                    style="border:0;" 
                    allowfullscreen="" 
                    loading="lazy">
            </iframe>
        </section>
        <section>
            <h2>Contacto</h2>
            <p>Para más información, no dudes en contactarnos:</p>
            <ul style="list-style-type: none; padding-left: 0;">
                <li><strong>Joshua Solis:</strong> <a href="tel:3315841619">331 584 1619</a></li>
                <li><strong>Francisco Antonio:</strong> <a href="tel:3310000793">331 000 0793</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>Contacto: info@dfprecision.com | Tel: +52 123 456 7890</p>
        <p>Síguenos en:
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">LinkedIn</a>
        </p>
    </footer>
    <a href="https://wa.me/523315841619" target="_blank" style="position: fixed; bottom: 20px; right: 20px; background-color: #25D366; color: white; padding: 15px; border-radius: 50%; text-decoration: none; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);">
        <i class="fab fa-whatsapp" style="font-size: 24px;"></i>
    </a>
</body>
</html>
