<!DOCTYPE html>
<html lang="en_US">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <meta name="description" content="MistyBlunch's portafolio">
  <meta name="keywords" content="portafolio,grace nikole alvarado,mistyblunch, developer">
  <meta name="author" content="MistyBlunch">
  <meta name="google" content="notranslate" />
  <meta property="og:title" content="MistyBlunch, web developer">
  <meta property="og:image" content="src/portfolio_img.png">
  <meta property="og:description" content="Hi I'm a Web Developer from Lima, Peru 🇵🇪 
  and enthusiast for technology, code, music and art.">
  <title>MistyBlunch</title>
  <link rel="icon" href="src/square/me_chibi.jpg">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.5/css/bulma.min.css">
  <link href="https://fonts.googleapis.com/css?family=Quattrocento+Sans|Schoolbell&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles/main.css">
  <script src="https://kit.fontawesome.com/e92fa48c98.js"></script>
  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=UA-147891800-1"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'UA-147891800-1');
  </script>
</head>
<body class="body-page">
  <!-- Main Hero -->
  <section class="hero hero-princ is-fullheight">
    <div class="hero-body">
      <div class="lang-div">
        <select id="lang-opt" onchange="selectLan(this)">
          <option value="en">english</option>
          <option value="es">spanish</option>
        </select>
      </div>
      <div class="container hero-princ-container is-flex f-d-col center-y">
        <img class="gif-animated" src="src/gif/funny.gif" alt="chibi gif">
        <div class="hero-princ-content is-flex f-d-col center-y text">
          <h1 class="title has-text-white has-text-centered">
            Grace Nikole
          </h1>
          <h2 class="subtitle has-text-grey-lighter">
            Developer
          </h2>
        </div>
        <div class="social-media">
          <ul class="col is-flex">
            <li class="li-smedia">
              <a href="https://twitter.com/GraceNikole" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-twitter"></i>
              </a>
            </li>
            <li class="li-smedia">
              <a href="https://www.instagram.com/mistyblunch/" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-instagram"></i>
              </a>      
            </li>
            <li class="li-smedia">
              <a href="https://medium.com/@gracenikole" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-medium-m"></i>
              </a>      
            </li>
            <li class="li-smedia">
              <a href="https://www.youtube.com/channel/UCoKBkoGknv8JQOsjcRgs-tw?view_as=subscriber" target="_blank" rel="noopener noreferrer">
                <i class="fab fa-youtube"></i>
              </a> 
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="hero-princ-footer">
      <div class="container">
        <ul class="menu is-flex center-x">
          <a href="#about" class="no-deco">
            <li class="en-opt">About</li>
            <li class="es-opt">Acerca</li>
          </a>
          <li>/</li>
          <a href="#skills" class="no-deco">
            <li class="en-opt">Skills</li>
            <li class="es-opt">Habilidades</li>
          </a>
          <li>/</li>
          <a href="#projects" class="no-deco">
            <li class="en-opt">Projects</li>
            <li class="es-opt">Proyectos</li>
          </a>
          <li>/</li>
          <a href="#blog" class="no-deco">
            <li>Blog</li>
          </a>
          <li>/</li>
          <a href="#contact" onclick="toContact()" class="no-deco">
            <li class="en-opt">Contact</li>
            <li class="es-opt">Contacto</li>
          </a>
        </ul>
      </div>
    </div>
  </section>

  <!-- About -->
  <section class="hero about" id="about">
    <div class="columns about-columns">
      <div class="column about col-1 is-flex center-y center-x">
        <h1 class="title is-1 has-text-white en-opt">About</h1>
        <h1 class="title is-1 has-text-white es-opt">Acerca de mí</h1>
      </div>
      <div class="column about col-2">
        <div class="about-content">
          <h3 class="subtitle is-3 en-opt">Hi! 👋</h3>
          <h3 class="subtitle is-3 es-opt">Hola! 👋</h3>
          <h5 class="subtitle is-5 en-opt">
            I'm a Web Developer <br>
            and enthusiast for technology, code, music and art. <br>
          </h5>
          <h5 class="subtitle is-5 es-opt">
            Soy desarrolladora web<br>
            y entuasiasta por la tecnología, el código, la música
            y el arte. <br>
          </h5>
          <h6 class="subtitle is-6 en-opt">I write articles when I'm free about programming or tutorials, 
            you can find them in 
            <a href="https://medium.com/@gracenikole" target="_blank"rel="noopener noreferrer">Medium</a> 
            and in <a href="https://dev.to/mistyblunch" target="_blank" rel="noopener noreferrer">dev.to</a>. 
          </h6>
          <h6 class="subtitle is-6 es-opt">Escribo artículos cada que tengo tiempo acerca de programación 
            o tutoriales, puedes encontrarlos en
            <a href="https://medium.com/@gracenikole" target="_blank"rel="noopener noreferrer">Medium</a> 
            y también en <a href="https://dev.to/mistyblunch" target="_blank" rel="noopener noreferrer">dev.to</a>. 
          </h6>
          <br>
          <img src="src/square/me.jpg" class="about-img" alt="my photo">
          <h6 class="subtitle is-6 has-text-centered en-opt">I like this picture :3</h6>
          <h6 class="subtitle is-6 has-text-centered es-opt">Me gusta esta foto :3</h6>
          <br>
          <h6 class="subtitle is-6 en-opt">
            I'm searching to improve my knowledge in frontend technologies like JS, CSS and some libraries and frameworks, 
            and learn more about backend technologies too.
          </h6>
          <h6 class="subtitle is-6 es-opt">
            Actualmente estoy mejorando mis conocimientos en tecnologías frotend como JS, CSS y otra librerías y frameworks,
            y aprendiendo algunas cosas sobre backend.
          </h6>
          <h6 class="subtitle is-6 en-opt">
            For now I'm a student although I'm learning more things in books, YouTube videos and blogs too. 
            I really like reading programming posts I've always loved learning something new 💚
          </h6>
          <h6 class="subtitle is-6 es-opt">
            Por ahora soy estudiante, sin embargo, estoy aprendiendo más leyendo algunos libros, 
            viendo videos en YouTube o leyendo blogs.
            Realmente me encanta leer post de programación, siempre me ha gustado aprender algo nuevo 💚
          </h6>
          <h6 class="subtitle is-6 en-opt">
            When I'm free I go to music fairs to listen to bands play live too. I have a
            <a href="https://www.youtube.com/channel/UCoKBkoGknv8JQOsjcRgs-tw?view_as=subscriber" target="_blank" rel="noopener noreferrer">YouTube</a> 
            channel where I upload videos of my favorite bands.
          </h6>
          <h6 class="subtitle is-6 es-opt">
            Cuando estoy libre también me gusta ir a ferias para escuchar a bandas tocar en vivo, 
            de hecho, tengo un canal de 
            <a href="https://www.youtube.com/channel/UCoKBkoGknv8JQOsjcRgs-tw?view_as=subscriber" target="_blank" rel="noopener noreferrer">YouTube</a>
            en donde subo videos de mis bandas favoritas entre otras cosas.
          </h6>
          <h6 class="subtitle is-6 read-more" id="about-read-more" onclick="openReadMore(this.id)">
            Read More...
          </h6>
          <div id="about-read-more-section" class="read-more-section">
            <h5 class="subtitle is-5 en-opt">
              So, Do you want to know more about me? 👀 
            </h5>
            <h5 class="subtitle is-5 es-opt">
              Así que quieres conocerme más? 👀 
            </h5>
            <h6 class="subtitle is-6 en-opt">      
              Hahaha... Okay  
              <br>
              Here are some things about me and curiosities. 🐭  
            </h6>
            <h6 class="subtitle is-6 es-opt">      
              jajaajaja... Vale
              <br>
              Aquí te dejo algunas cosas sobre mí y curiosidades. 🐭  
            </h6>
            <h6 class="subtitle is-6 en-opt">
              When I started in the world of programming, one of the first things I did was a small 
              screen that opened from my computer that asked me for the password that I put in my 
              pseudocode to open a calculator and for me it was a lot of fun. I felt like a troll 
              asking for the password to use a simple calculator 👩🏼‍💻, after that and other things that
              I did I started to like the tech area because you will always need learning something new, 
              although sometimes it can be overwhelming, but at the same time fun.
            </h6>
            <h6 class="subtitle is-6 es-opt">
              Cuando comencé en el mundo de la programacion, una de las primeras cosas que hice fue una pequeña
              pantalla que se abría desde mi computadora y me preguntaba por una contraseña, la cual había 
              puesto en mi pseudocódigo para así poder abrir una calculadora, para mí fue muy divertido porque 
              me sentía toda troll pidiendo una contraseña para usar una simple calculadora 👩🏼‍💻, después de
              eso y otras cosas que hice me comenzó a gustar el área de tecnología, porque siempre necesitarás 
              aprender algo nuevo, aunque a veces puede ser abrumador, pero al mismo tiempo divertido.
            </h6>
            <h6 class="subtitle is-6 en-opt">
              After seeing pseudocode I used and worked with languages like C ++, PHP,
              Python and JS, but more with JS and Python.
            </h6>
            <h6 class="subtitle is-6 es-opt">
              Después de ver pseudocódigo comencé a usar y trabajar con lenguajes como C++, PHP, 
              Python y JS, pero más con JS y Python.
            </h6>
            <h6 class="subtitle is-6 en-opt">
              I think the best way to practice and learn more is sharing your knowledge with others and 
              it's very nice to do it 💛, because when I didn't know how to start in the world of programming, 
              opinions and advices from others were very useful for me. So, when I see people who don't 
              know how to start programming, I give them some recommendation or a link to a page so they can 
              learn and experiment without fear depending on what they like. 
            </h6>
            <h6 class="subtitle is-6 es-opt">
              Yo pienso que la mejor manera de practicar y aprender más es compartir tus conocimientos
              con otras personas y es muy bonito hacerlo 💛, porque cuando yo no sabía cómo comenzar en
              programación las opiniones y consejos de otros me fue de mucha ayuda. 
              Por eso, cuando veo a personas que no saben cómo comenzar les doy alguna recomendación o 
              links a páginas en donde ellos pueden aprender y experimentar sin miedo alguno dependiendo 
              de lo que les guste.
            </h6>
            <h6 class="subtitle is-6 en-opt">
              Sometimes I volunteer for workshops of organizations like <b>WAWA Laptop</b>, 
              <b>HackSpace</b>, <b>GIT (Girls Inspire Tech)</b> in Peru. I love being able to help.
            </h6>
            <h6 class="subtitle is-6 es-opt">
              A veces soy voluntaria en talleres de organizaciones como <b>WAWA Laptop</b>, 
              <b>HackSpace</b>, <b>GIT (Girls Inspire Tech)</b> en Peru. Me encanta poder ayudar como pueda.
            </h6>
            <h6 class="subtitle is-6 en-opt">
              One of my favorite hobbies is singing, so I like karaokes a lot 🎤, I also like acting, 
              watching horror and actions movies, going to art expositions and discovering new music.
            </h6>
            <h6 class="subtitle is-6 es-opt">
              Uno de mis hobbies favoritos es cantar, así que me gustan mucho los karaokes 🎤, 
              También me gusta actuar, ver películas de terror y acción, ir a exposiciones de 
              arte y descubrir nueva música.
            </h6>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section class="hero skills" id="skills">
    <div class="hero-body">
      <div class="container skills">
        <h1 class="title is-1 has-text-centered en-opt">What did I use in Tech?</h1>
        <h1 class="title is-1 has-text-centered es-opt">¿Qué tecnologías he usado?</h1>
        <div class="container programming">
          <h3 class="title is-3 en-opt">Programming</h3>
          <h3 class="title is-3 es-opt">Programación</h3>
          <div class="columns skills">
            <div class="img" data-desc="HTML 5">
              <img src="src/skills/html5.png" alt="html5 image">
            </div>
            <div class="img" data-desc="CSS 3">
              <img src="src/skills/css3.png" alt="css3 image">
            </div>
            <div class="img" data-desc="Javascript">
              <img src="src/skills/javascript.png" alt="javascript image">
            </div>
            <div class="img" data-desc="C++">
              <img src="src/skills/cplusplus.png" alt="C++ image">
            </div>
            <div class="img" data-desc="Python">
              <img src="src/skills/python.png" alt="Python image">
            </div>
          </div>
        </div>
        <div class="see-more-skills is-flex center-x">
          <a class="button is-rounded skills-more-btn no-deco" onclick="seeMoreSkills()">
            See More
          </a>
        </div>
        <div class="more-skills d-none">
          <div class="container css-libraries">
            <h3 class="title is-3 en-opt">CSS Tools</h3>
            <h3 class="title is-3 es-opt">Herramientas de CSS</h3>
            <div class="columns skills">
              <div class="img" data-desc="Bootstrap">
                <img src="src/skills/bootstrap.png" alt="Bootstrap image">
              </div>
              <div class="img" data-desc="SASS">
                <img src="src/skills/sass.png" alt="SASS image">
              </div>
            </div>
          </div>
          <div class="container css-libraries">
            <h3 class="title is-3 en-opt">Web Sites</h3>
            <h3 class="title is-3 es-opt">Sitios Web</h3>
            <div class="columns skills">
              <div class="img" data-desc="Wordpress">
                <img src="src/skills/wordpress.png" alt="Wordpress image">
              </div>
              <div class="img" data-desc="Wix">
                <img src="src/skills/wix.png" alt="Wix image">
              </div>
            </div>
          </div>
          <div class="container css-mail-mkt">
            <h3 class="title is-3 en-opt">Mailing and MKT</h3>
            <h3 class="title is-3 es-opt">Mailing y MKT</h3>
            <div class="columns skills">
              <div class="img" data-desc="Mailchimp">
                <img src="src/skills/mailchimp.png" alt="Mailchimp image">
              </div>
              <div class="img" data-desc="Hubspot">
                <img src="src/skills/hubspot.png" alt="Hubspot image">
              </div>
            </div>
          </div>
          <div class="container css-tools">
            <h3 class="title is-3 en-opt">Tools</h3>
            <h3 class="title is-3 es-opt">Herramientas</h3>
            <div class="columns skills">
              <div class="img" data-desc="Elementor">
                <img src="src/skills/elementor.png" alt="Elementor image">
              </div>
              <div class="img" data-desc="GIT">
                <img src="src/skills/git.png" alt="GIT image">
              </div>
              <div class="img" data-desc="AWS">
                <img src="src/skills/amazonaws.png" alt="AWS image">
              </div>
              <div class="img" data-desc="Linux">
                <img src="src/skills/linux.png" alt="Linux image">
              </div>
              <div class="img" data-desc="Zapier">
                <img src="src/skills/zapier.png" alt="Zapier image">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section class="hero projects" id="projects">
    <div class="hero-body">
      <div class="container projects-wrapper is-flex f-d-col center-x">
        <h1 class="title is-1 has-text-centered en-opt">what projects have I done?</h1>
        <h1 class="title is-1 has-text-centered es-opt">¿Qué proyectos hice?</h1>
        <div class="all-projects is-flex center-x center-y f-d-col">
          <div class="container projects">
            <!-- Elegimos.pe -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Elegimos.pe"
                data-link="https://www.elegimos.pe/"
                data-desc="Desarrollo de una página que permite filtrar a candidatos presidenciales, 
                congresales y del parlamento andino según su nivel educativo, sexo, edad, cantidad 
                de sentencias y más...💗"
                data-tools="Python, Django, PostgreSQL, Javascript"
                >
                <img class="project" src="src/projects/elegimos.png" alt="Elegimos.pe Project image">
              </div>
              <a href="https://www.elegimos.pe/" class="no-deco" target="_blank">
                Elegimos.pe Project
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Elegimos.pe"
                data-link="https://www.elegimos.pe/"
                data-desc="Development of a page that allows you to filter presidential, 
                congressional and Andean parliament candidates according to their educational 
                level, sex, age, number of sentences and more...💗"
                data-tools="Python, Django, PostgreSQL, Javascript"
                >
                <img class="project" src="src/projects/elegimos.png" alt="Proyecto Elegimos.pe imagen">
              </div>
              <a href="https://www.elegimos.pe/" class="no-deco" target="_blank">
                Proyecto Elegimos.pe
              </a>
            </div>

            <!-- Leauty -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Leauty Web Scraping"
                data-link="https://github.com/MistyBlunch/leauty"
                data-desc="This project consists of the web scraping 🕷 of libgen.is, a free library 
                of books, where I obtained the data from the books and showed them on a web page 
                with a more beautiful design."
                data-tools="Pyhton, BeautifulSoup, Flask, Jinja2"
                >
                <img class="project" src="src/projects/leauty.png" alt="Leauty web scraping image">
              </div>
              <a href="https://github.com/MistyBlunch/leauty" class="no-deco" target="_blank">
                Leauty Web Scraping
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Leauty Web Scraping"
                data-link="https://github.com/MistyBlunch/leauty"
                data-desc="Este proyecto consiste en usa una técnica para sacar datos(Web Scraping 🕷)  
                de libgen.is, una librería con ejemplares gratis, de donde se obtienen los datos de 
                los libros y después son mostrados en otra página con más bonito diseño."
                data-tools="Pyhton, BeautifulSoup, Flask, Jinja2"
                >
                <img class="project" src="src/projects/leauty.png" alt="Leauty web scraping imagen">
              </div>
              <a href="https://github.com/MistyBlunch/leauty" class="no-deco" target="_blank">
                Leauty Web Scraping
              </a>
            </div>

            <div class="hide-t">
              <!-- BCP Form -->
              <div class="column project has-text-centered en-opt">
                <div 
                  class="img-container" 
                  onclick="showProject(this)" 
                  data-title="BCP Form"
                  data-link="https://bolsadetrabajo.laborum.pe/bcpForm/"
                  data-desc="Form 📝 to apply for the job offers of BCP with a dashboard 
                  generated with DataTable that shows the data of the applicants taken 
                  from Firebase."
                  data-tools="HTML, JS, CSS, Firebase, Amazon S3, DataTable"
                  >
                  <img class="project" src="src/projects/bcp_form.png" alt="BCP Form image">
                </div>
                <a href="https://bolsadetrabajo.laborum.pe/bcpForm/" class="no-deco" target="_blank">
                  BCP Form
                </a>
              </div>
              <div class="column project has-text-centered es-opt">
                <div 
                  class="img-container" 
                  onclick="showProject(this)" 
                  data-title="BCP Formulario"
                  data-link="https://bolsadetrabajo.laborum.pe/bcpForm/"
                  data-desc="Formulario 📝 para postular a una oferta de trabajo del BCP 
                  con un dashboard generado por DataTable que muestra los datos de los 
                  postulantes traídos desde Firebase"
                  data-tools="HTML, JS, CSS, Firebase, Amazon S3, DataTable"
                  >
                  <img class="project" src="src/projects/bcp_form.png" alt="BCP Formulario imagen">
                </div>
                <a href="https://bolsadetrabajo.laborum.pe/bcpForm/" class="no-deco" target="_blank">
                  BCP Formulario
                </a>
              </div>
            </div>

            <!-- More Projects Button -->
            <div class="see-more-projects is-flex center-x">
              <a class="button is-rounded projects-more-btn no-deco" onclick="seeMoreProjects()">
                See More
              </a>
            </div>
          </div>
          <div class="container more-projects">
            <div class="show-t">
              <!-- BCP Form -->
              <div class="column project has-text-centered en-opt">
                <div 
                  class="img-container" 
                  onclick="showProject(this)" 
                  data-title="BCP Form"
                  data-link="https://bolsadetrabajo.laborum.pe/bcpForm/"
                  data-desc="Form 📝 to apply for the job offers of BCP with a dashboard 
                  generated with DataTable that shows the data of the applicants taken 
                  from Firebase."
                  data-tools="HTML, JS, CSS, Firebase, Amazon S3, DataTable"
                  >
                  <img class="project" src="src/projects/bcp_form.png" alt="BCP Form image">
                </div>
                <a href="https://bolsadetrabajo.laborum.pe/bcpForm/" class="no-deco" target="_blank">
                  BCP Form
                </a>
              </div>
              <div class="column project has-text-centered es-opt">
                <div 
                  class="img-container" 
                  onclick="showProject(this)" 
                  data-title="BCP Formulario"
                  data-link="https://bolsadetrabajo.laborum.pe/bcpForm/"
                  data-desc="Formulario 📝 para postular a una oferta de trabajo del BCP 
                  con un dashboard generado por DataTable que muestra los datos de los 
                  postulantes traídos desde Firebase"
                  data-tools="HTML, JS, CSS, Firebase, Amazon S3, DataTable"
                  >
                  <img class="project" src="src/projects/bcp_form.png" alt="BCP Formulario imagen">
                </div>
                <a href="https://bolsadetrabajo.laborum.pe/bcpForm/" class="no-deco" target="_blank">
                  BCP Formulario
                </a>
              </div>
            </div>

            <!-- Vinci Project -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Vinci - Roche"
                data-link="https://vincioncogen.com/#/login"
                data-desc="Desarrollo del front-end de la aplicación Vinci. 
                La aplicación consiste en formularios para que los doctores 👩‍⚕️
                adjunten información relevante de pacientes con cáncer en diversos hospitales."
                data-tools="Angular, Node.js, JS"
                >
                <img class="project" src="src/projects/vinci.png" alt="Vinci - Roche Project image">
              </div>
              <a href="https://vincioncogen.com/#/login" class="no-deco" target="_blank">
                Vinci - Roche Project
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Vinci - Roche"
                data-link="https://vincioncogen.com/#/login"
                data-desc="Development of the front-end of the Vinci application. 
                The application consists of forms for doctors 👩‍⚕️ to attach relevant 
                information of cancer patients in various hospitals."
                data-tools="Angular, Node.js, JS"
                >
                <img class="project" src="src/projects/vinci.png" alt="Proyecto Vinci - Roche imagen">
              </div>
              <a href="https://vincioncogen.com/#/login" class="no-deco" target="_blank">
                Proyecto Vinci - Roche
              </a>
            </div>

            <!-- Krowdy -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Krowdy Website"
                data-link="https://www.krowdy.com/"
                data-desc="This is a website to learn about Krowdy's services and technologies 🦄 
                and also to learn about Human Resources in its amazing Blog."
                data-tools="Wordpress, Elementor, Hubspot, Mailchimp"
                >
                <img class="project" src="src/projects/krowdy.png" alt="Krowdy Website image">
              </div>
              <a href="https://www.krowdy.com/" class="no-deco" target="_blank">
                Krowdy Website
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Krowdy Web"
                data-link="https://www.krowdy.com/"
                data-desc="Este es una página web para conocer acerca de las sevicios y tecnologías 🦄 
                de Krowdy y también para aprender acerca del área de Recursos Humanos en su increíble
                Blog."
                data-tools="Wordpress, Elementor, Hubspot, Mailchimp"
                >
                <img class="project" src="src/projects/krowdy.png" alt="Krowdy Web imagen">
              </div>
              <a href="https://www.krowdy.com/" class="no-deco" target="_blank">
                Krowdy Web
              </a>
            </div>

            <!-- Palindrome -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Palindrome Verification"
                data-link="https://mistyblunch.github.io/palindrome_numbers/"
                data-desc="This project verifies if your text or number is palindrome 
                and prints a text and a happy face 😃 if it's palindrome."
                data-tools="HTML, JS, CSS, Bootstrap Framework"
                >
                <img class="project" src="src/projects/palindrome.png" alt="Palindrome Verification image">
              </div>
              <a href="https://mistyblunch.github.io/palindrome_numbers/" class="no-deco" target="_blank">
                Palindrome Verification
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Verificación de capicúos"
                data-link="https://mistyblunch.github.io/palindrome_numbers/"
                data-desc="Este proyecto verifica si tu número o texto es capicúo o 
                palíndromo y luego imprime una carita feliz 😃 si lo es."
                data-tools="HTML, JS, CSS, Bootstrap Framework"
                >
                <img class="project" src="src/projects/palindrome.png" alt="Verificación de capicúos imagen">
              </div>
              <a href="https://mistyblunch.github.io/palindrome_numbers/" class="no-deco" target="_blank">
                Verificación de capicúos
              </a>
            </div>
            
            <!-- Demo Krowdy -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Demo Krowdy"
                data-link="https://demo.krowdy.com/"
                data-desc="This is a landing web to learn more about Krowdy's service explained with videos 🎥."
                data-tools="HTML, JS, CSS, Bulma Framework, Amazon S3"
                >
                <img class="project" src="src/projects/demo_krowdy.png" alt="Demo Krowdy image">
              </div>
              <a href="https://demo.krowdy.com/" class="no-deco" target="_blank">
                Demo Krowdy
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Demo de Krowdy"
                data-link="https://demo.krowdy.com/"
                data-desc="Landing para conocer los serevicios de Krowdy explicados por videos 🎥."
                data-tools="HTML, JS, CSS, Bulma Framework, Amazon S3"
                >
                <img class="project" src="src/projects/demo_krowdy.png" alt="Demo de Krowdy imagen">
              </div>
              <a href="https://demo.krowdy.com/" class="no-deco" target="_blank">
                Demo de Krowdy
              </a>
            </div>

            <!-- Cinemark -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Cinemark Landing"
                data-link="https://bolsadetrabajo.laborum.pe/cinemark/"
                data-desc="This is insight web 💡 for Cinemark to show your job offers
                available at Laborum(website where you can find work in Peru)."
                data-tools="HTML, CSS, Amazon S3"
                >
                <img class="project" src="src/projects/cinemark.png" alt="Cinemark Landing image">
              </div>
              <a href="https://bolsadetrabajo.laborum.pe/cinemark/" class="no-deco" target="_blank">
                Cinemark Landing
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Landing de Cinemark"
                data-link="https://bolsadetrabajo.laborum.pe/cinemark/"
                data-desc="Esta es una página insight 💡 de Cinemark para mostrar sus ofertas
                laborales disponibles en Laborum(sitio web en donde puedes encontrar trabajo en Perú)."
                data-tools="HTML, CSS, Amazon S3"
                >
                <img class="project" src="src/projects/cinemark.png" alt="Landing de Cinemark imagen">
              </div>
              <a href="https://bolsadetrabajo.laborum.pe/cinemark/" class="no-deco" target="_blank">
                Landing de Cinemark
              </a>
            </div>

            <!-- Blog -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Personal Blog"
                data-link="https://github.com/MistyBlunch/my_first_blog"
                data-desc="It was fun to make this blog since I was just beginning to learn 
                about web pages and I started with Django following a Django Girls tutorial, 
                I learned about the routes, templates and models 🐰"
                data-tools="Pyhton, Django, CSS"
                >
                <img class="project" src="src/projects/django.jpeg" alt="Personal Blog image">
              </div>
              <a href="https://github.com/MistyBlunch/my_first_blog" class="no-deco" target="_blank">
                Personal Blog
              </a>
            </div>   
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Blog Personal"
                data-link="https://github.com/MistyBlunch/my_first_blog"
                data-desc="Fue muy divertido hacer este blog ya que recién estaba comenzando 
                a aprender sobre las páginas web y comencé con Django siguiendo el tutorial de 
                Django Girls. Aprendí sobre las rutas, modelos y plantillas 🐰"
                data-tools="Pyhton, Django, CSS"
                >
                <img class="project" src="src/projects/django.jpeg" alt="Blog Personal imagen">
              </div>
              <a href="https://github.com/MistyBlunch/my_first_blog" class="no-deco" target="_blank">
                Blog Personal
              </a>
            </div> 

            <!-- P5 Animations -->
            <div class="column project has-text-centered en-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="p5.js Animations"
                data-link="https://github.com/MistyBlunch/examples-with-p5.js"
                data-desc="I really like when an object moves, so I like the animations, in this project 
                I used p5.js, a JS library to play with them and create fun things ✨"
                data-tools="HTML, JS, p5.js library"
                >
                <img class="project" src="src/projects/p5js.png" alt="p5.js Animations image">
              </div>
              <a href="https://github.com/MistyBlunch/examples-with-p5.js" class="no-deco" target="_blank">
                p5.js Animations
              </a>
            </div>
            <div class="column project has-text-centered es-opt">
              <div 
                class="img-container" 
                onclick="showProject(this)" 
                data-title="Animaciones con p5.js"
                data-link="https://github.com/MistyBlunch/examples-with-p5.js"
                data-desc="Me gusta mucho cuando un objeto se mueve, por eso me gustan las animaciones, 
                en este proyecto usé la librería de JS llamada p5.js para jugar con ella y crear cosas 
                divertidas ✨"
                data-tools="HTML, JS, p5.js library"
                >
                <img class="project" src="src/projects/p5js.png" alt="Animaciones con p5.js imagen">
              </div>
              <a href="https://github.com/MistyBlunch/examples-with-p5.js" class="no-deco" target="_blank">
                Animaciones con p5.js
              </a>
            </div>

            
            <!-- Add more... -->
          </div>
        </div>   
      </div>
    </div>
    <div id="project-popup" class="hero project d-none">
      <div class="hero-body is-flex center-y">
        <a class="close project" onclick="closeProject()">&times;</a>
        <div class="container">
          <div class="columns">
            <div class="column is-two-thirds is-flex center-y">
              <a id="project-link" target="_blank">
                <img class="img-project" id="project-img">
              </a>
            </div>
            <div class="column project-desc">
              <h4 class="title is-4" id="project-name"></h4>
              <div class="characteristics">
                <div class="container">
                  <h5 class="subtitle is-5 en-opt">Technologies</h5>
                  <h5 class="subtitle is-5 es-opt">Tecnologías</h5>
                  <ul class="lis" id="project-list">
                  </ul>
                </div>
    
                <div class="container">
                  <h5 class="subtitle is-5 en-opt">About the Project?</h5>
                  <h5 class="subtitle is-5 es-opt">¿Acerca del Proyecto?</h5>
                  <h6 class="subtitle is-6" id="project-desc"></h6>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="hero hero-contact is-fullheight stick" id="contact">
    <div class="hero-body is-flex f-d-col">
      <div class="container hero-contact-container is-flex f-d-col center-y center-x">
        <div class="hero-contact-content is-flex center-y f-d-col text">
          <h2 class="title is-2 has-text-white has-text-centered en-opt">
            Want to get in touch?
          </h2>
          <h2 class="title is-2 has-text-white has-text-centered es-opt">
            ¿Quieres ponerte en Contacto?
          </h2>
          <h4 class="subtitle is-4 has-text-white has-text-centered is-spaced en-opt">
            Find me on Twitter, Instagram, Medium, Dev.to, GitHub or YouTube
          </h4>
          <h4 class="subtitle is-4 has-text-white has-text-centered is-spaced es-opt">
            Encuentrame en Twitter, Instagram, Medium, Dev.to, GitHub o en YouTube
          </h4>
        </div>
        <div class="social-media">
          <ul class="col is-flex center-x f-wrap">
              <li class="li-smedia">
                <a href="https://twitter.com/GraceNikole" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-twitter en-opt" title="Follow me on Twitter"></i>
                  <i class="fab fa-twitter es-opt" title="Sígueme en Twitter"></i>
                </a>
              </li>
              <li class="li-smedia">
                <a href="https://www.instagram.com/mistyblunch/" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-instagram en-opt" title="Follow me on Instagram"></i>
                  <i class="fab fa-instagram es-opt" title="Sígueme en Instagram"></i>
                </a>      
              </li>
              <li class="li-smedia">
                <a href="https://medium.com/@gracenikole" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-medium-m en-opt" title="Follow me on Medium"></i>
                  <i class="fab fa-medium-m es-opt" title="Sígueme en Medium"></i>
                </a>      
              </li>
              <li class="li-smedia">
                <a href="https://dev.to/mistyblunch" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-dev en-opt" title="Follow me on Dev.to"></i>
                  <i class="fab fa-dev es-opt" title="Sígueme en Dev.to"></i>
                </a>
              </li>
              <li class="li-smedia">
                <a href="https://github.com/MistyBlunch" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-github en-opt" title="Follow me on GitHub"></i>
                  <i class="fab fa-github es-opt" title="Sígueme en GitHub"></i>
                </a> 
              </li>
              <li class="li-smedia">
                <a href="https://www.youtube.com/channel/UCoKBkoGknv8JQOsjcRgs-tw?view_as=subscriber" target="_blank" rel="noopener noreferrer">
                  <i class="fab fa-youtube en-opt" title="Follow me on YouTube"></i>
                  <i class="fab fa-youtube es-opt" title="Sígueme en YouTube"></i>
                </a> 
              </li>
          </ul>
        </div>
        <div class="emailme">
          <h6 class="subtitle is-6 has-text-white has-text-centered en-opt">
            Or email me at 
            <a href="mailto:gracenikole@gmail.com?Subject=Hi%20Grace!%20I%20come%20from%20your%20website" 
              class="no-deco"
              target="_blank" 
              rel="noopener noreferrer"
            >
              gracenikole@gmail.com
            </a>
          </h6>
          <h6 class="subtitle is-6 has-text-white has-text-centered es-opt">
            O envíame un email a 
            <a href="mailto:gracenikole@gmail.com?Subject=Hi%20Grace!%20I%20come%20from%20your%20website" 
              class="no-deco"
              target="_blank" 
              rel="noopener noreferrer"
            >
              gracenikole@gmail.com
            </a>
          </h6>
        </div>
      </div>
      <div class="copyrig">
        <h6 class="subtitle is-6 has-text-white">
          © Copyright <span id="current_year"></span>. MistyBlunch
        </h6>
      </div>
    </div>
  </section>

  <!-- Loader -->
  <div id="loader_ctn">
    <img src="src/gif/loader.svg" alt="">
  </div>
</body>
<script src="js/index.js"></script>
</html>