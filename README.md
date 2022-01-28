# curso-esencial-html-css


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./style-logical.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,700;1,400&family=Roboto:ital,wght@0,400;0,600;0,700;1,400;1,700&display=swap"
    rel="stylesheet">

  <link rel="apple-touch-icon" sizes="57x57" href="./favicon/apple-icon-57x57.png">
  <link rel="apple-touch-icon" sizes="60x60" href="./favicon/apple-icon-60x60.png">
  <link rel="apple-touch-icon" sizes="72x72" href="./favicon/apple-icon-72x72.png">
  <link rel="apple-touch-icon" sizes="76x76" href="./favicon/apple-icon-76x76.png">
  <link rel="apple-touch-icon" sizes="114x114" href="./favicon/apple-icon-114x114.png">
  <link rel="apple-touch-icon" sizes="120x120" href="./favicon/apple-icon-120x120.png">
  <link rel="apple-touch-icon" sizes="144x144" href="./favicon/apple-icon-144x144.png">
  <link rel="apple-touch-icon" sizes="152x152" href="./favicon/apple-icon-152x152.png">
  <link rel="apple-touch-icon" sizes="180x180" href="./favicon/apple-icon-180x180.png">
  <link rel="icon" type="image/png" sizes="192x192" href="./favicon/android-icon-192x192.png">
  <link rel="icon" type="image/png" sizes="32x32" href="./favicon/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="96x96" href="./favicon/favicon-96x96.png">
  <link rel="icon" type="image/png" sizes="16x16" href="./favicon/favicon-16x16.png">
  <link rel="manifest" href="/manifest.json">
  <meta name="msapplication-TileColor" content="#ffffff">
  <meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
  <meta name="theme-color" content="#ffffff">

  <title>El blog de Laymón</title>
</head>
<body>
  <div class="hero"></div>
<div class="header">
  <div class="wrapper">
    <div class="header-content">
      <header>
        <nav>
          <details open>
            <summary>
              Setup
            </summary>
            <ol>
              <li><a href="#google-chrome">Google Chrome</a></li>
              <li><a href="#vsc">Visual Studio Code</a></li>
              <li><a href="#figma">Figma</a></li>
              <li><a href="#github">GitHub</a></li>
            </ol>
          </details>

          <details open>
            <summary>
              Conceptos esenciales del Desarrollo Web
            </summary>
            <ol>
              <li><a href="#html">Qué es HTML</a></li>
              <li><a href="#etiquetas">Etiquetas</a></li>
              <li><a href="#dom">DOM</a></li>
              <li><a href="#semantica">Semántica</a></li>
              <li><a href="#atributos">Atributos</a></li>
              <li><a href="#css">Qué es CSS</a></li>
            </ol>
          </details>

        </nav>
      </header>
    </div>
  </div>
</div>
  <main class="main">

    <div class="wrapper">
      <div class="main-content">
        <h1>Curso esencial de HTML y CSS</h1>
        <p>
          Este es el inicio de tu carrera como Desarrollador Web, empezarás aprendiendo HTML y CSS para la creación de
          contenidos,
          en el nivel 2 aprenderás de componentes y en 3 sobre layouts.
        </p>
        <hr>
        <section class="section-content">
          <h2>
            Setup
          </h2>
          <img src="images/google_chrome.jpg" alt="Logo de Google Chrome" title="Logo de Google Chrome">
          <h3 id="google-chrome">
            Google Chrome
          </h3>
          <p>
            Chrome va a ser el navegador que utilizaremos en el curso por su extenso soporte de nuevos estándares y herramientas
            de
            desarrollo avanzadas y de amigable uso.
          </p>
          <img src="images/visual_studio_code.jpg" alt="Logo de Visual Studio Code" title="Logo de Visual Studio Code">
          <h3 id="vsc">
            Visual Studio Code
          </h3>
          <p>
            Visual Studio Code es el editor de texto más popular y potente del mercado actualmente, su fácil uso y la capacidad
            de
            extenderlo por medio de plugins lo hace el complemento perfecto para cualquier programador sin importar el lenguaje
            en
            el que se desemvuelva.
          </p>
          <img src="images/figma.jpg" alt="Logo de Figma" title="Logo de Figma">
          <h3 id="figma">
            Figma
          </h3>
          <p>
            Figma es una la herramienta más popular en la actualidad para entregar diseños a los desarrolladores para su
            implementación por su fácil uso porque puede ser usado directamente desde el navegador.
          </p>
          <img src="images/github.jpg" alt="Logo de GitHub" title="Logo de GitHub">
          <h3 id="github">
            GitHub
          </h3>
          <p>
            Así como en Facebook te encuentran tus amigos, en Github te encuentran otras programadoras y programadores de todo
            el
            mundo, en vez de subir fotos de tus viajes aquí subes tu código y puedes elegir hacerlo “open source” o guardarlo de
            manera privada, Github será esencial para almacenar tu futuro portafolio.
          </p>
          <blockquote>
            <p>
              “Este es el inicio de tu carrera como Desarrollador Web”
            </p>
            <p>
              <span>
                Leonidas Esteban
              </span>

            </p>


          </blockquote>
        </section>
        <hr>
        <section class="section-content">
          <h2>
            Conceptos esenciales del Desarrollo Web
          </h2>
          <h3 id="html">
            Qué es HTML
          </h3>
          <p>
            Hyper Text Markup Language o Lenguaje de marcas Hipertexto. Es el componente más básico de la web. Define el
            significado
            y la estructura del contenido.
          </p>
          <pre>
&lt;!DOCTYPE html&gt;
&lt;html lang=&quot;en&quot;&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta http-equiv=&quot;X-UA-Compatible&quot; content=&quot;IE=edge&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;title&gt;Document&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;

&lt;/body&gt;
&lt;/html&gt;
                </pre>
          <h3 id="etiquetas">Etiquetas</h3>
          <p>Las etiquetas HTML van a ayudarnos a brindar una estructura y semántica al contenido de nuestro website y cada una
            tiene
            características y usos diferentes aunque visualmente den un resultado similar.</p>
          <p>Muchas etiquetas son fácil de diferencias como los headings o las imágenes y otras diferentes como header, footer,
            section o div, aquí es donde la semántica será la respuesta y si sabemos un poco de inglés también podremos darnos
            una
            pequeña idea de su uso pero en este curso vamos a usar las más importantes y que serán parte de tu día a día como
            Software Developer.</p>
          <h3 id="dom">DOM</h3>
          <p>El Document Object Model es una estructura de árbol que representará todos nuestros proyectos web como si un árbol
            genealógico fuera: padres, hijos, hermanos con niveles infinitos. cuando entendemos esta anidación podemos
            identificar
            dependencias, herencias en css y que tan complejo es nuestro proyecto.</p>
          <img class="img_dom" src="images/dom.png" alt="Es un ejemplo del Dom" title="Imagen del Dom">
          <h3 id="semantica">Semántica</h3>
          <p>La semántica le brinda sentido a cada elemento existen en un sitio web, algunos elementos será meramente
            decorativos
            y
            no deben significar nada pero otros serán títulos y deberán estar en diferente jerarquías o alguna secciones serán
            más
            relevantes que otras, esto ayudará a los motores de búsqueda como Google o Duck Duck Go a diferenciar tu contenido,
            categorizar y será la herramientas más valiosa para estar en los primeros resultados de búsqueda SEO. También
            ayudará
            a
            la accesibilidad de tu sitio web, para que personas con habilidades diferentes puedan entender cada contenido.</p>
          <h3 id="atributos">Atributos</h3>
          <p>Los atributos le dan características extra a las etiquetas para complementar información y son pre programadas por
            el
            navegador, algunos atributos funcionan en todas las etiquetas de la misma forma como ‘class’ pero otros atributos
            funcionan en solo alguna etiquetas como src</p>
          <h3 id="css">CSS</h3>
          <p>Hojas de Estilo en Cascada (del inglés Cascading Style Sheets) o CSS es el lenguaje de estilos utilizado para
            describir
            la presentación de documentos HTML</p>
          <img src="images/image_css.png" alt="Imagen CSS" title="Imagen de CSS">
        </section>
        <section class="section-content">
          <h2>Modelo de Caja</h2>
          <h3>El modelo de caja está compuesto por:</h3>
          <p>Chrome va a ser el navegador que utilizaremos en el curso por su extenso soporte de nuevos estándares y
            herramientas
            de
            desarrollo avanzadas y de amigable uso.</p>
          <ol>
            <li>Tamaño del del contenido / ancho y alto</li>
            <li>Padding / Relleno</li>
            <li>Border / Bordes</li>
            <li>Margin / Márgenes</li>
          </ol>
          <h3>Propiedades físicas para el modelo de caja:</h3>
          <ul>
            <li>width / height</li>
            <li>margin / margin-top | margin-right | margin-bottom | margin-left</li>
            <li>border / border-top | border-right | border-bottom | border-left</li>
            <li>padding / padding-top | padding-right | padding-bottom | padding-left</li>
          </ul>
          <h3>Propiedades lógicas para el modelo de caja:</h3>
          <ul>
            <li>inline-size / block-size</li>
            <li>margin-block | margin-inline | margin-block-start | margin-block-end | margin-inline-start | margin-inline-end
            </li>
            <li>border-block | border-inline | border-block-start | border-block-end | border-inline-start | border-inline-end
            </li>
            <li>padding-block | padding-inline | padding-block-start | padding-block-end | padding-inline-start |
              padding-inline-end</li>
          </ul>
          <h3>Modelo de caja</h3>
          <img src="images/modelo_caja.png" alt="Ejemplo de modelo de Caja" title="Modelo de Caja">


          <a href="https://leonidasesteban.com/" target="_blank">leonidasesteban</a>
        </section>
        <div class="section-content">
          <h2>Hola estos son algunos video muy lindos</h2>
          <div class="slider">
            <scroll-container class="slider-container">
              <scroll-page class="slider-slide" id="video-1">

                <iframe class="video" width="560" height="315" src="https://www.youtube.com/embed/UhzlM28dHiY" title="YouTube video player"
                  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
              </scroll-page>
              <scroll-page class="slider-slide" id="video-2">

                <iframe class="video" width="560" height="315" src="https://www.youtube.com/embed/UhzlM28dHiY" title="YouTube video player"
                  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
              </scroll-page>
              <scroll-page class="slider-slide" id="video-3">

                <iframe class="video" width="560" height="315" src="https://www.youtube.com/embed/UhzlM28dHiY" title="YouTube video player"
                  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
              </scroll-page>
              <scroll-page class="slider-slide" id="video-4">

                <iframe class="video" width="560" height="315" src="https://www.youtube.com/embed/UhzlM28dHiY" title="YouTube video player"
                  frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
              </scroll-page>
            </scroll-container>
            <div class="slider-bullet-list">
              <a href="#video-1" class="slider-bullet"></a>
              <a href="#video-2" class="slider-bullet"></a>
              <a href="#video-3" class="slider-bullet"></a>
              <a href="#video-4" class="slider-bullet"></a>
            </div>
          </div>
        </div>

        <p> Si tienes alguna pregunta escríbeme a
         <a href="mailto:jlaymonch@gmail.com">jlaymonch@gmail.com</a>
        </p>
        <div class="section-content">
          <h2>Ingresa a nuestro newletter</h2>
          <form action="#" class="form">
            <input type="text" required placeholder="Nombre">
            <input type="email" required placeholder="Correo Electrónico">
            <input type="submit" value="Suscribirme">
          </form>
        </div>
      </div>
    </div>

  </main>

</body>
</html>

