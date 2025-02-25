# Portafolio-de-evidencias-de-programacion-web-1
Portafolio de evidencias de programacion web 1
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio - Programación Web I</title>
    <style>
        .actividades {
            display: none;
        }
    </style>
    <script>
        function mostrarActividades() {
            var actividades = document.getElementById("actividadesUnidad1");
            if (actividades.style.display === "none" || actividades.style.display === "") {
                actividades.style.display = "block";
            } else {
                actividades.style.display = "none";
            }
        }
    </script>
</head>
<body>
    <h1>Portafolio</h1>
    <h2>Programación Web I</h2>
    <p>182003 Braulio Carrizales Hernandez</p>

    <h3 onclick="mostrarActividades()">Unidad No. 1</h3>
    <ul id="actividadesUnidad1" class="actividades">
        <li>Actividad No. 1 (Hola mundo) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_1_index.html">link</a></li>
        <li>Actividad No. 2 (Títulos) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_2_1_index.html">link</a></li>
        <li>Actividad No. 2-1 (Mapa de sitio) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_2_1_index.html">link</a></li>
        <li>Actividad No. 3 (Párrafo) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_3_index.html">link</a></li>
        <li>Actividad No. 4 (Listas I) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_4_index.html">link</a></li>
        <li>Actividad No. 4-1 (Plan de estudios) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_4_1_index.html">link</a></li>
        <li>Actividad No. 5 (Listas II) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_5_index.html">link</a></li>
        <li>Actividad No. 6 (Widget) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_6_index.html">link</a></li>
        <li>Actividad No. 7 (Enlaces) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_7_index.html">link</a></li>
        <li>Actividad No. 8 (Imagenes) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_8_index.html">link</a></li>
        <li>Actividad No. 9-1 (Quimica Organica) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_9_1_index.html">link</a></li>
        <li>Actividad No. 9 (Formatos) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_9_index.html">link</a></li>
        <li>Actividad No. 10 (Mapa) <a href="file:///C:/Users/ROBERT/OneDrive/Desktop/Parcial%201%20Portafolio%20web/Actividad_10_index.html">link</a></li>
    </ul>

    <h3>Unidad No. 2</h3>
    <ul>
        <!-- Añadir actividades de la Unidad No. 2 aquí -->
    </ul>

    <h3>Unidad No. 3</h3>
    <ul>
        <li>Proyecto</li>
    </ul>
</body>
</html>
