<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ficha3</title>
    <style>
        /* Eliminamos el espacio de arriba del todo */
        body { font-family: Arial, sans-serif; text-align: center; margin: 0; padding: 5px 20px 20px 20px; background-color: #f4f6f9; }
        
        /* Reducimos al mínimo los márgenes del único título para que no empuje el PDF */
        h1 { margin-top: 5px; margin-bottom: 5px; }
        p { margin-top: 0; margin-bottom: 10px; }

        /* Contenedor pegado al texto superior */
        .contenedor-pdf { width: 85%; height: 650px; margin: 0 auto 20px auto; border: 1px solid #cbd5e1; box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1); background-color: #fff; border-radius: 8px; overflow: hidden; }
        .btn-descarga { display: inline-block; margin-top: 15px; padding: 12px 24px; background-color: #007bff; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; transition: background 0.2s; }
        .btn-descarga:hover { background-color: #0069d9; }
    </style>
</head>
<body>

    <!-- ÚNICO TÍTULO DE LA PÁGINA -->
    <h1>Ficha3</h1>
    <p>Reforzar Conocimientos - Actividades Finales</p>
    
    <!-- VISOR DE FICHA 3 -->
    <div class="contenedor-pdf">
        <iframe src="Ficha3.pdf" width="100%" height="100%" style="border: none;">
            Tu navegador no soporta la visualización de PDFs. 
            <a href="Ficha3.pdf">Haz clic aquí para ver el documento.</a>
        </iframe>
    </div>

    <!-- BOTÓN DE DESCARGA DIRECTA -->
    <a href="Ficha3.pdf" download class="btn-descarga">Descargar Ficha3</a>

</body>
</html>
