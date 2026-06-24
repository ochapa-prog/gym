<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gimnasio Base - Nombre de la Pestaña</title>
    <style>
        *, *::before, *::after {
            box-sizing: border-box;
        }
        body {
            background-color: #f5f5f5;
            color: #222222;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #111111;
            color: #ffffff;
            padding: 60px 20px;
            text-align: center;
        }
        h1 {
            color: #ffcc00;
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        .btn-gym {
            background-color: #ffcc00;
            color: #111111;
            border: none;
            padding: 15px 30px;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
            font-size: 1.1rem;
            text-decoration: none;
            display: inline-block;
            margin-top: 15px;
        }
        .btn-gym:hover {
            background-color: #e6b800;
        }
        main {
            padding: 40px 20px;
            text-align: center;
            background-color: #ffffff;
            max-width: 800px;
            margin: 0 auto;
        }
        .gallery {
            display: block;
            margin: 20px 0;
        }
        .gallery-img {
            width: 100%;
            max-width: 500px;
            height: auto;
            margin: 15px auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            display: block;
        }
        footer {
            background-color: #222222;
            color: #cccccc;
            padding: 30px 20px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>GIMNASIO URBANO</h1>
        
        <p>Tu entrenamiento empieza hoy. Fuerza, salud y comunidad en un solo lugar.</p>
        
        <a href="https://www.smartfit.com" target="_blank" class="btn-gym">¡Inscríbete Ahora en Smart Fit!</a>
    </header>

    <main>
        <h2>Nuestros Planes y Servicios</h2>
        <p>Ofrecemos zona de pesas, cardio, entrenamiento funcional y entrenadores personalizados para cumplir tus metas.</p>
        
        <div class="gallery">
            <h3>Nuestras Instalaciones</h3>
            <img class="gallery-img" src="https://images.unsplash.com/photo-1534438327276-14e5300c3a48?auto=format&fit=crop&w=600&q=80" alt="Zona de Pesas del Gimnasio">
            <img class="gallery-img" src="https://images.unsplash.com/photo-1517838277536-f5f99be501cd?auto=format&fit=crop&w=600&q=80" alt="Entrenamiento Funcional">
        </div>
    </main>

    <footer>
        <h3>Contacto y Ubicación</h3>
        <p>📍 Dirección: Av. Principal 123, Ciudad</p>
        <p>📞 Teléfono: +593 99 999 9999</p>
        <p>✉️ Correo: info@gimnasioficticio.com</p>
    </footer>

</body>
</html>
