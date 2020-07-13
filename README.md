<!DOCTYPE html>
<html lang="es"> 
    <head>
        <meta charset="utf-8"/>
        <title>Bastian Cerda</title>
        <link rel="icon" type="image/png" href="imagenes/logo.jpg" />
        <link href="https://fonts.google.com/specimen/Source+Sans+Pro?query=source"/>
        <link rel="stylesheet" href="css/Estilos.css">
    </head>
    <body>
        <div>
            <header class="header"> 
                <div>
                    <figure class="logo">
                        <img src="Imagenes/logo.jpg " alt="Logo de http://bastiancerda.com" width="5%">
                    </figure>
                    <nav class="menu">
                        <ol>
                            <li>
                                <a class="link" href="#portafolio">Portafolio</a>
                            </li>
                            <li>
                                <a class="link" href="#Experiencia">Experiencia</a>
                            </li>
                            <li>
                                <a class="link" href="#contactos">Trabajemos juntos</a>
                            </li>
                        </ol>
                    </nav>
                </div>
            </header>
            <section class="hero">
                <h1>Bienvenido <br/> Yo soy <strong>Bastian Cerda</strong> <br/> y estoy <strong>aprendiendo a programar</strong> un Sitio Web</h1>
                <figure class="hero-image">
                    <img src="Imagenes/florencio2.0.jpg" width="20%"/>
                </figure>
            </section>
            <section id="portafolio" class="portfolio">
                <h2>Portafolio ( Proyectos Destacados)</h2>
                <article class="project">
                    <div class="project-details">
                        <h3 class="project-title">Pagina de Github</h3>
                        <h6 class="project-course">Palabras /foto</h6>
                        <p class="project-date"><small><strong>Fecha:</strong> 12/07/2020</small></p>
                        <p class="project-url"><small><strong>Puedes verlo presionando</strong> <a href="http://bastianalen.github.io">aquí</a> </small></p>
                        <p class="project-description">Resultado de practicas por cuenta propia en html</p>
                    </div>
                    <figure class="project-imageContainer">
                        <img class="project-image" src="imagenes/cartel.jpg"  alt="Primer cartel de la nave de los locos" width="100%"/>
                    </figure>
                </article>
            </section>
            <section id="Experiencia">
                <h2>Más sobre mi Experiencia</h2>
                <article class="event">
                <figure class="event-imageContainer">
                    <img class="event-image" src="Imagenes/florencio.jpg" width="20%"/>
                </figure>
                <h3 class="event-title">Presentación en Plaza de Armas 2018</h3>
                <p class="event-description">Uno de los primeros eventos de la nave de los locos se realizo en la Plaza de Armas de melipilla con la intencion de entretener a un publico diverso y ademas ganar conocimiento de actuacón</p>
                <a class="event-url" href="http://bastianalen.github.io">Ver Imagenes</a>
                </article>
            </section>
            <section id="contactos" class="contact">
                <form action="/suscripcion" class="form-email">
                    <h3 >¿Trabajemos juntos?</h3>
                    <input type="text" placeholder="Ingrese su correo">
                    <button>Enviar</button>
                </form>
            </section>
            <footer class="footer">footer</footer>
        </div>
    </body>
</html>