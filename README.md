<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Para Elisa, minha vida 🌷</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <audio autoplay loop>
    <source src="lisboa.mp3" type="audio/mpeg" />
    Seu navegador não suporta áudio :(
  </audio>

  <div class="container">
    <h1>Para Elisa, minha tulipa 💖</h1>
    
    <div class="typing" id="carta">
      <!-- Texto será digitado aqui -->
    </div>

    <div class="jogo">
      <h2>Encontre o coração verdadeiro 💘</h2>
      <div class="coraçoes">
        <button onclick="verificarCoraçao(this)">💔</button>
        <button onclick="verificarCoraçao(this)">💘</button> <!-- certo -->
        <button onclick="verificarCoraçao(this)">💔</button>
      </div>
      <p id="mensagem-jogo"></p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
<!-- Cartinha de amor -->
<div class="cartinha">
  <h2>Lindona </h2>
  <p id="typed-text"></p>
</div>

<!-- Player do Spotify -->
<div class="musica">
  <p style="text-align:center; font-weight: bold;">ouço e penso em vc 💖</p>
  <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/2o2xhyri4aJUtgMGkf5P0J?utm_source=generator&theme=0" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>
