# P-gina-web-tesa-and-darling
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Tesa & Darling</title>
  <style>
    body {
      background-color: #fff0f6;
      font-family: 'Georgia', serif;
      color: #333;
      text-align: center;
      padding: 30px;
    }
    h1 {
      color: #c71585;
      font-size: 2.5em;
    }
    .foto {
      width: 85%;
      max-width: 400px;
      border-radius: 15px;
      margin: 20px auto;
    }
    .seccion {
      margin: 40px 0;
    }
    .corazon {
      font-size: 1.5em;
      color: #ff69b4;
    }
  </style>
</head>
<body>
  <h1>Tesa & Darling</h1>

  <div class="seccion">
    <p>Éramos dos amigas de curso... hasta que el <strong>efecto mariposa</strong> hizo su magia.</p>
    <p>Una pequeña decisión —un grupo de trabajo— lo cambió todo.</p>
  </div>

  <div class="seccion">
    <img src="https://i.imgur.com/pOE0jL0.jpg" class="foto" alt="Nosotras">
  </div>

  <div class="seccion">
    <p>Si tú no me hubieras hablado, yo no te habría conocido como te conozco ahora...</p>
    <p>Y no estaría escribiéndote esto, sonriendo, amándote.</p>
    <span class="corazon">♡</span>
  </div>

  <div class="seccion">
    <p><em>"Don’t Blame Me"</em> suena, y yo solo pienso en vos.</p>
  </div>

  <div class="seccion">
    <p>Gracias por existir, Darling.</p>
    <p>Con amor, siempre,</p>
    <p><strong>Tesa</strong></p>
  </div>

  <div class="seccion">
    <p>Te amo con todo lo que soy, y te elegiría en esta vida... y en todas las que vengan.</p>
    <p>Sos el <strong>efecto mariposa más único</strong> que he tenido, y nada me hace más feliz que haber coincidido con vos.</p>
    <p>No importa cuánto nos cueste a veces, o qué caminos vengan... yo te voy a seguir amando, con todo lo que tengo.</p>
  </div>

  <!-- Reproductor de audio oculto y bajito -->
  <audio autoplay loop hidden id="miAudio">
    <source src="https://voca.ro/16hoy6zNImhG" type="audio/mpeg">
    Tu navegador no soporta la reproducción de audio.
  </audio>

  <script>
    window.onload = function() {
      const audio = document.getElementById("miAudio");
      audio.volume = 0.15;
    }
  </script>
</body>
</html>
