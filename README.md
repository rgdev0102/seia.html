<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sensores industriales</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
        }

        .fila-superior {
            height: 25%;
            background: #ffffff url('cabecera.png') center/cover no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .fila-inferior {
            height: 60%;
            display: flex;
        }

        .columna {
            border: 2px solid #094;
            padding: 10px;
        }

        .columna-1 {
            flex: 1;
            width: 10%;
            overflow-y: auto; /* Agrega scroll vertical si el contenido excede el tamaño de la columna */
            max-height: 100%; /* Ajusta la altura máxima para que se ajuste al tamaño de la fila */
        }


        .columna-1 .indice {
            text-align: left; /* Alinea el texto al centro en la primera columna */
            padding-left: 10; /* Elimina el relleno izquierdo en la primera columna */
        }

        .columna-2 {
            flex: 8;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .contenido-final {
             text-align: center; /* Centra el contenido horizontalmente */
             margin-top: 20px;   /* Ajusta el margen superior para agregar un espacio */
        }


        .indice {
            list-style-type: none;
            padding: 0;
        }

        .indice li {
            margin-bottom: 5px;
        }
        
        .contenido_indice {
            margin-left: 20px;
        }

        .iframe-container {
            width: 100%;
            height: 100%;
        }

        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div class="fila-superior">
        <!-- Contenido de la fila superior -->
        <h8>SEIA - CAT 'web en construcció' </h8>
    </div>

    <div class="fila-inferior">
        <div class="columna columna-1">
            <ul class="indice">
                <li><a>Tipos de sensores (Descripción basica): </a></li>
                <li><a href="#seccion1">1. Sensor Inductivo Digital</a></li>
                <li><a href="#seccion2">2. Sensor Capacitivo</a></li>
                <li><a href="#seccion3">3. Sensor Fotoeléctrico</a></li>
                <li><a href="#seccion4">4. Sensor de Ultrasonidos</a></li>
                <li><a href="#seccion5">5. Sensor Tipo Galgas Extensiométricas</a></li>
            </ul>
        </div>
        <div class="columna columna-2">
            <div class="iframe-container">
                <iframe src="https://bookdown.org/alberto_brunete/intro_automatica/sensores-industriales.html" title="Contenido externo"></iframe>
            </div>
        </div>
    </div>

    <div class="contenido_indice">
        <div id="seccion1" style="margin-bottom: 20px; overflow: auto;">
            <h2 style="clear: both;">1. Sensor Inductivo Digital</h2>
            <div class="imagen-con-comentario" style="overflow: auto;">
                <a href="https://es.wikipedia.org/wiki/Sensor_inductivo" style="float: left;">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Inductivo_histeresis.jpg" style="max-width: 200px; height: auto; margin-right: 10px;">
                </a>
                <div style="float: right; width: calc(100% - 220px);">
                    <p style="float: left;">Los sensores inductivos digitales detectan la presencia o ausencia de un objeto mediante la variación en la inductancia. Son comúnmente utilizados en aplicaciones de conteo y control de posición.</p>
                    <b class="comentario" style="clear: both; float: left;">Para más información sobre los sensores inductivos hacer clic en la imagen.</b>
                </div>
            </div>
        </div>
        
        <div id="seccion2" style="margin-bottom: 20px; overflow: auto;">
            <h2 style="clear: both;">2. Sensor Capacitivo</h2>
            <div class="imagen-con-comentario" style="overflow: auto;">
                <a href="https://es.wikipedia.org/wiki/Sensor_capacitivo" style="float: left;">
                    <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcRtDEB0Tk9zN_fDaOC5bXyIhuCBx4SYgDerB7ib8tyqvC6Kv2XF_1hefzsEfScRwkB4GUq2CJ1MoJd4AjURTrPf0ZL-8QfajRBq6AORefVwRs2d1g-KzZ7aYTdw6N_CtT5bbfPmvvDPRw&usqp=CAc" style="max-width: 200px; height: auto; margin-right: 10px;">
                </a>
                <div style="float: right; width: calc(100% - 220px);">
                    <p style="float: left;">Los sensores capacitivos detectan cambios en la capacitancia causados por la presencia de un objeto. Son ideales para la detección de materiales no metálicos y se utilizan en sistemas de nivel y control de líquidos.</p>
                    <b class="comentario" style="clear: both; float: left;">Para más información sobre los sensores capacitivos hacer clic en la imagen.</b>
                </div>
            </div>
        </div>
        
        <div id="seccion3" style="margin-bottom: 20px; overflow: auto;">
            <h2 style="clear: both;">3. Sensor Fotoeléctrico</h2>
            <div class="imagen-con-comentario" style="overflow: auto;">
                <a href="https://es.wikipedia.org/wiki/Sensor_fotoel%C3%A9ctrico" style="float: left;">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/Light_sensor.png" style="max-width: 200px; height: auto; margin-right: 10px;">
                </a>
                <div style="float: right; width: calc(100% - 220px);">
                    <p style="float: left;">Estos sensores utilizan luz para detectar la presencia o ausencia de un objeto. Son ampliamente utilizados en sistemas de conteo, clasificación y control de posición en la industria.</p>
                    <b class="comentario" style="clear: both; float: left;">Para más información sobre los sensores fotoeléctricos hacer clic en la imagen.</b>
                </div>
            </div>
        </div>
        
    
        <div id="seccion4" style="margin-bottom: 20px; overflow: auto;">
            <h2 style="clear: both;">4. Sensor de Ultrasonidos</h2>
            <div class="imagen-con-comentario" style="overflow: auto;">
                <a href="https://es.wikipedia.org/wiki/Sensor_ultras%C3%B3nico" style="float: left;">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/HC_SR04_Ultrasonic_sensor_1480322_3_4_HDR_Enhancer.jpg/330px-HC_SR04_Ultrasonic_sensor_1480322_3_4_HDR_Enhancer.jpg" style="max-width: 200px; height: auto; margin-right: 10px;">
                </a>
                <div style="float: right; width: calc(100% - 220px);">
                    <p style="float: right;">Emplean ondas ultrasónicas para medir la distancia a un objeto. Se utilizan en aplicaciones de medición de nivel, detección de obstáculos y sistemas de estacionamiento automático en vehículos.</p>
                    <b class="comentario" style="clear: both; float: left;">Para más información sobre los sensores ultrasónicos hacer clic en la imagen.</b>
                </div>
            </div>
        </div>
        
        <div id="seccion5" style="margin-bottom: 20px; overflow: auto;">
            <h2 style="clear: both;">5. Sensor Tipo Galgas Extensiométricas</h2>
            <div class="imagen-con-comentario" style="overflow: auto;">
                <a href="https://es.wikipedia.org/wiki/Galga_extensiom%C3%A9trica" style="float: left;">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Strain_gauge.svg/330px-Strain_gauge.svg.png" style="max-width: 200px; height: auto; margin-right: 10px;">
                </a>
                <div style="float: right; width: calc(100% - 220px);">
                    <p style="float: right;">Las galgas extensiométricas miden la deformación de un objeto bajo carga. Son esenciales en la medición de fuerza y la monitorización de la tensión en estructuras como puentes y edificios.</p>
                    <b class="comentario" style="clear: both; float: left;">Para más información sobre los sensores ultrasónicos hacer clic en la imagen.</b>
                </div>
            </div>
        </div>
              
    
    <div class="contenido-final">
        <STRONG>- Página web Codigo HTML by Juan M. Perez Lechado AIRI 23-24 1R Curs -</STRONG>
    </div>
</body>
</html>
