!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio</title>
    <link rel="stylesheet" type="text/css" media="screen" href="./estilos.css">
    <link rel="stylesheet" href="estilos.css">
    <style>
        .footer {
            text-align: center;
            background-color: #2d2f3e;
            color: rgb(15, 15, 15);
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .footer img {
            margin-left: 10px; /* Ajuste el margen izquierdo según sea necesario */
            height: 30px; /* Ajuste el tamaño de la imagen */
            vertical-align: middle; /* Alinear verticalmente con el texto */
        }

        .footer p {
            margin-left: 10px; /* Ajuste el margen izquierdo del texto */
            display: inline-block;
            vertical-align: middle;
        }
    </style>
</head>

<body>
    <main class="main">
        <section class="section-1">
            <header class="header">
                <div class="img">
                    <img src="RECTA.JPG" alt="Logo de la página">
                </div>  
                <nav class="menu">
                    <a href="Pagina de Yojoa/Yojoa.HTML">Yojoa</a>
                    <a href="Achiote/paginaprincipal.html">Achiote</a>
                    <a href="Buenos Aires/paginaBuenosAires.html">Buenos Aires</a>
                    <a href="Balin/Balin.html">Balin</a>
                </nav>
                
            </header>
        </section>
        <section class="section-2">
            <article class="s2-textos">
                <h2 class="bienvenidos">¿CONOCES ALGUNAS DE ESTAS COMUNIDADES?</h2>
                <hr>
                <p>A continuación te mostramos algunas de ellas :</p>
                <div class="video-container">
            </article>
            <div class="s2-img-container">
                <div class="contenido-img">
                    <img src="YojoaIMG.JPG" alt="">
                    <div class="contenido-texto">
                        <CENTER><h2>YOJOA</h2></CENTER>
                        <p>Descubre todo lo que nuestra comunidad tiene para ti:</p>
                        <p>•Iglesia.</p>
                        <p>•Escuela.</p>
                        <p>•Colegios.</p>
                        <p>•Parque.</p>
                        <p>•Campo.</p>
                    

                       
                    </div>
                </div>
                <div class="contenido-img">
                    <img src="Achiote.JPG" alt="Introducción a la Programación">
                    <div class="contenido-texto">
                        <CENTER><h2>ACHIOTE</h2></CENTER>
                        <p>Conoce los rincones de nuestra comunidad:</p>
                        <p>•Peceras.</p>
                        <p>•Iglesias.</p>
                        <p>•Escuela.</p>
                        <p>•Campo.</p>
                
                    </div>
                </div>
                <div class="contenido-img">
                    <img src="Buenos Aires.jpeg" alt="Introducción a la Programación">
                    <div class="contenido-texto">
                        <CENTER><h2>BUENOS AIRES</h2></CENTER>
                        <p>Explora nuestra comunidad aqui encontraras lugares como:</p>
                        <p>•Nacimiento.</p>
                        <p>•Iglesias.</p>
                        <p>•Escuela.</p>
                        <p>•Campo.</p>
                        <p>•Cementerio.</p>
                     
                    </div>
                </div>
                <div class="contenido-img">
                    <img src="Balin.jpeg" alt="Logo de la página">
                    <div class="contenido-texto">
                        <CENTER><h2>  BALIN   </h2></CENTER>
                        <p>Aqui tienes un recorrido por nuestra comunidad:</p>
                        <p>•Las Ramadas.</p>
                        <p>•La Clarita.</p>
                        <p>•Escuela.</p>
                        <p>•Campo.</p>
                       
                </div>
            </div>

            </div>
            <footer class="footer">
                <img src="logo1.jpeg" alt="Logo de la página" class="footer-logo">
                <p style="color: white; display: inline-block; vertical-align: middle; margin-left: 5px;">
                    Calle CA-5 Instituto Gubernamental Yojoa</p>
                &copy; <a href="#"> 2024</a>
            </footer>
        </section>
    </main>
</body>

</html>

/* estiloscss.css */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-x: hidden; /* Oculta el desbordamiento horizontal */
}



.main {
    width: 100%;
    min-height: 100vh;
    padding-top: 4em; /* Ajuste para evitar solapamiento con la barra de inicio */
}

.section-1 {
    width: 100%;
    height: 5em;
    background: linear-gradient(90deg, #ecdd53, #e2ffb5); /* Gradiente corregido */
    padding-top: 1.5em;
}

.header {
    background-color: #2d2f3e;
    width: 100%;
    height: 4em;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 1em;
    position: fixed;
    top: 0;
    z-index: 1000;
}

.img {
    background-color:  #e2ffb5;
    width: 20%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.img img {
    max-width: 100%;
    max-height: 100%;
    object-fit: cover; /* Ajuste para que la imagen se ajuste al contenedor sin deformarse */
}

.menu {
    background-color: #e2ffb5;
    width: 30%;
    height: 100%;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    align-items: center;
}

.menu a {
    text-decoration: none;
    color: #0c0c0c;
    padding: 1em 1.5em;
    transition: background-color 0.3s;
}

.menu a:hover {
    background-color: #de87f0; /* Color de fondo al pasar el ratón */
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-x: hidden; /* Oculta el desbordamiento horizontal */
}

.section-2 {
    width: 100%;
    background: #b4834d; 
    padding-top: 1em; /* Reducción del espacio superior */
    text-align: center; /* Alineación centrada del contenido */
}

.s2-textos {
    text-align: center; /* Alineación central del texto */
    margin-bottom: 4em; /* Espacio inferior entre el título y las imágenes */
}

.s2-img-container {
    display: flex;
    justify-content: space-around; /* Espaciado uniforme entre las imágenes */
    flex-wrap: wrap; /* Ajuste para que las imágenes se envuelvan correctamente */
    margin-top: 1em; /* Reducción del espacio superior */
    margin-bottom: 7em; /* Espacio inferior entre las imágenes y el texto */
}

.contenido-img {
    width: 22%; /* Ancho ajustado para mostrar las tres imágenes en una fila */
    padding: 0 1em; /* Añadido espacio interno a los lados */
    box-sizing: border-box; /* Asegura que el padding no incremente el tamaño total */
    display: flex;
    flex-direction: column;
    align-items: center; /* Centra el contenido verticalmente */
}

.contenido-img img {
    width: 105%;
    height: 30%;
    margin-top: -50px;
}

.contenido-texto {
    width: 280px; /* Ancho de la caja */
    height: 340px; /* Alto de la caja */
    background-color: rgb(253, 203, 170); /* Fondo gris claro para el contenido */
    padding: 2em;
    text-align: justify; /* Justifica el texto */
    margin-top: 0.5em; /* Espacio superior */

}

.contenido-texto h2 {
    font-size: 1.5em;
    margin-bottom: 0.5em;
}

.contenido-texto p {
    margin-bottom: 1em;
    font-size: 110%;
}

.contenido-texto a {
    color: #ff5500;
    text-decoration: none;
    font-weight: bold;
}

.contenido-texto a:hover {
    text-decoration: underline;
}

/* Estilos para la tercera imagen */
.s3-logo {
    width: 30%; /* Ajuste el ancho según sea necesario */
    padding: 0 1em; /* Espacio interno a los lados */
    box-sizing: border-box; /* Asegura que el padding no incremente el tamaño total */
    display: flex;
    flex-direction: column;
    align-items: center; /* Centra el contenido verticalmente */
}

.s3-logo img {
    width: 100%;
    height: auto;
}

.s3-logo .contenido-texto {
    background-color: #b4834d; /* Fondo gris claro para el contenido */
    padding: 1.5em;
    text-align: justify; /* Justifica el texto */
    margin-top: 0.5em; /* Espacio superior */
    width: 300px;
    height: 320px;
    float: right;
}

.s3-logo .contenido-texto h2 {
    font-size: 1.5em;
    margin-bottom: 0.5em;
}

.s3-logo .contenido-texto p {
    margin-bottom: 1em;
}

.s3-logo .contenido-texto a {
    color: #ff5500;
    text-decoration: none;
    font-weight: bold;
}

.s3-logo .contenido-texto a:hover {
    text-decoration: underline;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-x: hidden; /* Oculta el desbordamiento horizontal */
}

/* Estilos para la sección 3 */
.section-3 {
    text-align: center;
    margin-top: 3em; /* Espacio superior */
    padding: 2em 0; /* Añadido padding superior e inferior */
}

.section-3 .s3-contenido {
    margin-bottom: 2em; /* Espacio inferior */
}

.section-3 .s3-textos {
    margin-bottom: 0.5em;
}

video {
    width: 220px; /* Ancho del video */
    height: 200px; /* Mantener la relación de aspecto del video */
    border-radius: 20px; /* Bordes redondeados */
    margin-top: 50px; /* Ajusta el valor para mover el video hacia abajo */
}

.btn-regresar {
    background-color: #f8d3ab; /* Color de fondo */
    color: rgb(9, 199, 247); /* Color del texto */
    border: none; /* Sin borde */
    border-radius: 5px; /* Bordes redondeados */
    padding: 10px 20px; /* Espaciado interno */
    font-size: 20px; /* Tamaño de fuente */
    cursor: pointer; /* Cambia el cursor al pasar el mouse */
    transition: background-color 0.3s, transform 0.2s; /* Transiciones suaves */
    border-radius: 60px;
}

![image](https://github.com/user-attachments/assets/ef86acb7-b37c-4ebe-8f89-a6d42f9472a8)
![image](https://github.com/user-attachments/assets/0e924a0b-67c9-45fa-92a6-fc840ec402ee)
![image](https://github.com/user-attachments/assets/ac6bdeba-5876-4371-a4d2-f29795a719e1)
![image](https://github.com/user-attachments/assets/964bb433-83f3-40e2-a8ed-8dee2a7324f4)
![image](https://github.com/user-attachments/assets/a1aa21db-3b54-41bd-bd32-9e0916c19a65)
![image](https://github.com/user-attachments/assets/f26ac173-5aeb-49ac-b803-2743fa58cae6)
