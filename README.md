<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, user-scalable=no">
    <title></title>
    <link href='http://fonts.googleapis.com/css?family=Roboto+Condensed' rel='stylesheet' type='text/css'>
        <style>
        html, body {
    height: 20%;
  }
  .svg-wrapper {
    height: 10px;
  	margin: 10 auto;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    width: 320px;
  }
  .shape {
    fill: transparent;
    stroke-dasharray: 140 540;
    stroke-dashoffset: -474;
    stroke-width: 8px;
    stroke: #19f6e8;
  }
  .text {
    color: black;
    font-family: 'Roboto Condensed';
    font-size: 22px;
    letter-spacing: 8px;
    line-height: 32px;
    position: relative;
    top: -48px;
  }
  @keyframes draw {
    0% {
      stroke-dasharray: 140 540;
      stroke-dashoffset: -474;
      stroke-width: 20px;
    }
    100% {
      stroke-dasharray: 760;
      stroke-dashoffset: 0;
      stroke-width: 2px;
    }
  }
  .svg-wrapper:hover .shape {
    -webkit-animation: 0.5s draw linear forwards;
    animation: 0.5s draw linear forwards;
  }
      </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>
  </head>
  <body>
    <header>
      <div class="svg-wrapper">
      <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
        <rect class="shape" height="60" width="320" />
      </svg>
       <div class="text">Manuel Arias</div>
    </div><br/><br/>
      <h1>Hoja de Vida</h1>
      <h2>Manuel Arias</h2>
    </header>
    <section>
      <ul>
        <li><a href="index.html" id="Inicio">Inicio</a></li>
        <li><a href="educacion.html" id="Educación" title="Educación">Educación</a></li>
        <li><a href="experiencia.html" id="Experiencia" title="Experiencia">Experiencia</a></li>
      </ul>
    </section>
    <section>
      <h3>Educación</h3>
      <table border="1" id="tabla1" cellpadding="5" cellspacing="0">
        <thead>
          <tr>
            <th>Año</th>
            <th>Institucion</th>
            <th>Lugar</th>
            <th>Culmino</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>2006</td>
            <td>Injuv</td>
            <td>Bogotá</td>
            <td>Si</td>
          </tr>
          <tr>
            <td>2018</td>
            <td>Universidad de la cun</td>
            <td>Bogotá</td>
            <td>No</td>
          </tr>
        </tbody>
      </table>
    </section>
    <hr/>
    <section>
      <h3>Agregar Educación</h3>
      <form name="formContacto" autocomplete="on" action novalidate>
        <p>
          <label for="ano">Año:</label><br/>
          <input type="number" min="1990" max="2016" id="ano" placeholder="Ej:2005" required >
        </p>
        <p>
          <label for="institucion">Institución:</label><br/>
          <input type="text" name="institucion" placeholder="Ej: Universidad Nacional" id="institucion" required>
        </p>
        <p>
            <label for="lugar">Lugar:</label><br/>
            <textarea name="Lugar" rows="1" cols="30" required></textarea>
        </p>
        <p>
          <label for="culmino">Culmino:</label>
          <input type="radio" name="culmino" id="culmino">Si
          <input type="radio" name="culmino" id="culmino">No

        </p>
        <p>
          <label for="subir" id="Subir"></label>
          <input type="submit" name="subir" value="Submit" required>
        </p>
      </form>
    </section>
    <footer>
      <p><em> ® Derechos Reservados </em></p>
      <ul>
        <li><strong>Email:</strong><a href="mailto:sjmontoya@hotmail.com?subject=feedback" >sjmontoyav@hotmail.com</a></li>
        <li><strong>Telefono:</strong>3213224666</li>
        <li><strong>Direccion:</strong>Av. Calle Falsa 123</li>
      </ul>
    </footer>
  </body>
</html>
 experiencia.html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, user-scalable=no">
    <title></title>
    <link href='http://fonts.googleapis.com/css?family=Roboto+Condensed' rel='stylesheet' type='text/css'>
        <style>
        html, body {
    height: 20%;
  }
  .svg-wrapper {
    height: 10px;
  	margin: 10 auto;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    width: 320px;
  }
  .shape {
    fill: transparent;
    stroke-dasharray: 140 540;
    stroke-dashoffset: -474;
    stroke-width: 8px;
    stroke: #19f6e8;
  }
  .text {
    color: black;
    font-family: 'Roboto Condensed';
    font-size: 22px;
    letter-spacing: 8px;
    line-height: 32px;
    position: relative;
    top: -48px;
  }
  @keyframes draw {
    0% {
      stroke-dasharray: 140 540;
      stroke-dashoffset: -474;
      stroke-width: 20px;
    }
    100% {
      stroke-dasharray: 760;
      stroke-dashoffset: 0;
      stroke-width: 2px;
    }
  }
  .svg-wrapper:hover .shape {
    -webkit-animation: 0.5s draw linear forwards;
    animation: 0.5s draw linear forwards;
  }
      </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>
  </head>
  <body>
    <header>
      <div class="svg-wrapper">
      <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
        <rect class="shape" height="60" width="320" />
      </svg>
       <div class="text">Manuel Arias</div>
    </div><br/><br/>
      <h1>Hoja de Vida</h1>
      <h2>Manuel Arias</h2>
    </header>
    <section>
      <ul>
        <li><a href="index.html" id="Inicio">Inicio</a></li>
        <li><a href="educacion.html" id="Educación" title="Educación">Educación</a></li>
        <li><a href="experiencia.html" id="Experiencia" title="Experiencia">Experiencia</a></li>
      </ul>
    </section>
    <section>
      <h3>Experiencia</h3><hr/>
      <h3>Video: Todo sobre mi</h3>
      <video src="video/videofile.ogg" autoplay poster="img/profile.jpg" controls width="25%" height="30%"></video>
      <p><em>Todo sobre Mi - Video</em></p><hr/>

    </section>
    <section>
    <h3>Audio:Todo sobre Mi</h3>
    <audio src="audio/audio.ogg" controls>No se puede reproducir</audio><br/>
    <p><em>Todo sobre Mi - Audio Completo</em></p>
    </section>
    <footer>
      <p><em>Derechos Reservados (R)</em></p>
      <ul>
        <li><strong>Email:</strong><a href="mailto:manuelarias96@gmail.com?subject=feedback" >jose.ariass@cun.edu.co</a></li>
        <li><strong>Telefono:</strong>5555555</li>
        <li><strong>Direccion:</strong>Av. Calle Falsa 123</li>
      </ul>
    </footer>
  </body>
</html>
 index.html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, user-scalable=no">
    <title>Mi HV</title>
    <link href='http://fonts.googleapis.com/css?family=Roboto+Condensed' rel='stylesheet' type='text/css'>
        <style>
        html, body {
    height: 20%;
  }
  .svg-wrapper {
    height: 10px;
  	margin: 10 auto;
    position: relative;
    top: 50%;
    transform: translateY(-50%);
    width: 320px;
  }
  .shape {
    fill: transparent;
    stroke-dasharray: 140 540;
    stroke-dashoffset: -474;
    stroke-width: 8px;
    stroke: #19f6e8;
  }
  .text {
    color: black;
    font-family: 'Roboto Condensed';
    font-size: 22px;
    letter-spacing: 8px;
    line-height: 32px;
    position: relative;
    top: -48px;
  }
  @keyframes draw {
    0% {
      stroke-dasharray: 140 540;
      stroke-dashoffset: -474;
      stroke-width: 20px;
    }
    100% {
      stroke-dasharray: 760;
      stroke-dashoffset: 0;
      stroke-width: 2px;
    }
  }
  .svg-wrapper:hover .shape {
    -webkit-animation: 0.5s draw linear forwards;
    animation: 0.5s draw linear forwards;
  }
      </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js"></script>
  </head>
  <body>
    <header>
      <div class="svg-wrapper">
      <svg height="60" width="320" xmlns="http://www.w3.org/2000/svg">
        <rect class="shape" height="60" width="320" />
      </svg>
       <div class="text">Sebastian Montoya</div>
    </div><br/><br/>
      <h1>Hoja de Vida</h1>
      <h2>Manuel Arias</h2>
    </header>
    <section>
      <ul>
        <li><a href="index.html" id="Inicio">Inicio</a></li>
        <li><a href="educacion.html" id="Educación" title="Educación">Educación</a></li>
        <li><a href="experiencia.html" id="Experiencia" title="Experiencia">Experiencia</a></li>
      </ul>
    </section>
    <section>
      <h3>Datos Personales</h3>
      <img src="img/profile.jpg" alt="Foto_Perfil" title="Foto_Perfil" width="25%" height="25%">
      <ul>
        <li><strong>Nombre:</strong>Manuel</li>
        <li><strong>Apellido:</strong>Arias</li>
        <li><strong>Edad:</strong>30</li>
      </ul>
      <h3>Información de Perfil</h3>
      <ul>
        <li><strong>Perfil:</strong>Estudiante de Economía</li>
        </ul>
    </section>
    <footer>
      <p><em>® Derechos Reservados </em></p>
      <ul>
        <li><strong>Email:</strong><a href="mailto:sjmontoya@hotmail.com?subject=feedback" >sjmontoyav@hotmail.com</a></li>
        <li><strong>Telefono:</strong>3102640930</li>
        <li><strong>Direccion:</strong>Av. Calle Falsa 123</li>
      </ul>
    </footer>
  </body>
</html>
