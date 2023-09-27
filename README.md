# MasPrintPeru
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mas Print Perú</title>
    <style>
        body {
            background-color: black;
            color: green;
            text-align: center;
            font-size: 18px;
            font-family: Arial, sans-serif;
        }

        h1 {
            font-size: 36px;
        }

        .contenedor {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            padding: 20px;
        }

        .producto {
            background-color: gray; /* Cambia el color de fondo a gris */
            color: white; /* Cambia el color del texto a blanco */
            padding: 40px;
            margin: 20px;
            border: 4px solid green;
            border-radius: 20px;
            width: calc(38.33% - 24px);
            background-size: cover;
            background-position: center;
            text-align: center;
        }
        

        .redes-sociales a {
            background-color: transparent; /* Establece el fondo transparente */
            color: green;
            text-decoration: none;
            padding: 5px 10px;
            margin: 5px;
            border: 2px solid green;
            border-radius: 5px;
            transition: background-color 0.3s ease; /* Agrega una transición suave al color de fondo */
        }

        .redes-sociales a:hover {
            background-color: green; /* Cambia el color de fondo al pasar el cursor */
            color: white;
        }

       .contacto {
    background-color: transparent; /* Establece el fondo transparente */
    padding: 10px;
    margin: 20px;
    border-radius: 10px;
      }
        a {
            color: green;
            text-decoration: none;
        }

        /* Imágenes de fondo para cada casilla de producto */
        .producto:nth-child(1) {
            background-image: url('Franela.jpg');
        }

        .producto:nth-child(2) {
            background-image: url('Tapa soles.jpg');
        }

        .producto:nth-child(3) {
            background-image: url('Polos\ publicitarios.jpg');
        }

        .producto:nth-child(4) {
            background-image: url('Mangas.jpg');
        }

        .producto:nth-child(5) {
            background-image: url('servicio de estampados.jpg');
        }

        .producto:nth-child(6) {
            background-image: url('bolsita tematico.jpg');
        }

        /* Estilos para los detalles de los productos */
        .producto h1 {
            font-size: 24px;
            margin-bottom: 15px;
        }

        .producto p {
            font-size: 20px;
            margin-bottom: 10px;
        }
        /* Estilos para los nombres de productos con fondo de resalte */
.producto h2 {
    font-size: 24px;
    margin-bottom: 10px;
    padding: 5px; /* Añade un espacio entre el texto y el fondo */
    background-color: black; /* Color de fondo negro */
    color: white; /* Texto en color blanco para resaltar */
    border-radius: 5px; /* Añade esquinas redondeadas al fondo */
    display: inline-block; /* Hace que el fondo abarque solo el ancho del texto */
}
/* Aumenta el tamaño de letra específicamente para las líneas deseadas */
.producto p:nth-child(2), /* 30x33 = 1,40 por millar */
.producto p:nth-child(3), /* 23x30 = 1.20 por millar */
.producto p:nth-child(4), /* Detalle: a un solo color */
.producto p:nth-child(5), /* 30x72 = 2.20 por millar */
.producto p:nth-child(6), /* Estandar = 7 soles por cada 100 */
.producto p:nth-child(7), /* Detalle: a un solo color */
.producto p:nth-child(8), /* 2 soles por millar */
.producto p:nth-child(9), /* Al agua y plastisol */
.producto p:nth-child(10) /* c/u por docena = 4.5 soles */ {
    font-size: 18px; /* Tamaño de letra ligeramente más grande */
}



        body {
            background-image: url('fondo.jpg'); /* Establece la imagen de fondo */
            background-size: cover;
            background-position: center;
            background-attachment: fixed; /* Mantiene la imagen de fondo fija mientras se desplaza */
            background-repeat: no-repeat;
        }
        /* Estilos para el título "Mas Print Peru" */
h1 {
    font-size: 60px; /* Aumenta el tamaño de la letra */
}

/* Estilos para todo el contenido de la página */
body {
    font-size: 23px; /* Aumenta el tamaño de la letra en todo el cuerpo de la página */
}

    </style>
</head>
<body>
    <h1>Mas Print Perú</h1>
    
    <!-- Productos -->
    <div class="contenedor">
        <div class="producto">
            <h2>Franela</h2>
            <p>30x33 = 1,40 por millar</p>
            <p>23x30 = 1.20 por millar</p>
            <p>Detalle: a un solo color</p>
        </div>

        <div class="producto">
            <h2>Tapasoles</h2>
            <p>30x72 = 2.20 por millar</p>
        </div>

        <div class="producto">
            <h2>Polos Publicitarios</h2>
            <p>Estandar = 7 soles por cada 100</p>
            <p>Detalle: a un solo color</p>
        </div>

        <div class="producto">
            <h2>Mangas</h2>
            <p>2 soles por millar</p>
        </div>

        <div class="producto">
            <h2>Servicio de Estampados</h2>
            <p>Al agua y plastisol</p>
        </div>

        <div class="producto">
            <h2>Bolsitos Temáticos</h2>
            <p>c/u por docena = 4.5 soles</p>
        </div>
        <!-- Añade dos nuevas casillas -->
<div class="producto" style="background-image: url('ambientador.jpg');">
    <h2>Ambientadores Publicitarios</h2>
</div>

<div class="producto" style="background-image: url('cartuchera.jpg');">
    <h2>Cartucheras</h2>
</div>

    </div>

    <!-- Enlaces a redes sociales -->
    <div class="redes-sociales">
        <a href="https://www.facebook.com/masprintperu" target="_blank">Facebook</a>
        <a href="https://www.instagram.com/mas_print_peru/" target="_blank">Instagram</a>
        <a href="https://wa.me/981412799" target="_blank">WhatsApp</a>
        <a href="https://www.google.com/maps/dir//MAS+PRINT+PERU/data=!4m8!4m7!1m0!1m5!1m1!1s0x9105be5e8205d68f:0xf210696717a44927!2m2!1d-76.866354!2d-12.186437999999999" target="_blank">Cómo llegar</a>
    </div>

    <!-- Información de contacto -->
    <div class="contacto">
        <p>Contacto: 981412799</p>
        <p>Contacto: Juanjo</p>
    </div>
    
</body>
</html>

