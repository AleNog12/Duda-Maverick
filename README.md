<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>Pedido de Namoro</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    background-color: #f3e5f5;
    text-align: center;
    margin-top: 50px;
  }
  h2 {
    color: #ab47bc;
  }
  p {
    color: #666;
    font-size: 18px;
    margin: 20px auto;
    max-width: 600px;
  }
  .button {
    background-color: #ab47bc;
    color: white;
    border: none;
    padding: 10px 20px;
    text-transform: uppercase;
    margin-top: 20px;
    cursor: pointer;
  }
  .button:hover {
    background-color: #9c27b0;
  }
  #video, #noButton {
    display: none;
    margin-top: 20px;
  }
</style>
</head>
<body>

<h2>Quer ser minha namorada?</h2>
<p>Desde o momento em que te vi, meu mundo se encheu de cores. Você trouxe alegria e sentido para minha vida de uma forma que eu nunca imaginei possível. Cada sorriso seu ilumina meu dia e cada olhar seu aquece meu coração. Quero poder fazer você tão feliz quanto você me faz todos os dias. Então, o que você acha, vamos embarcar nessa aventura juntos?</p>

<button class="button" onclick="showVideo()">Sim, quero!</button>
<button class="button" onclick="noAnswer()">Não quero</button>

<div id="video">
  <p>Aqui está um vídeo especial para nós dois:</p>
  <!-- O 'embed' do vídeo do YouTube -->
  <iframe width="560" height="315" src="https://www.youtube.com/embed/DM47R2-GIGM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<div id="noButton">
  <p>Que pena! Aqui está um vídeo para você:</p>
</div>

<script>
function showVideo() {
  document.getElementById('video').style.display = 'block';
}

function noAnswer() {
  window.location.href = "https://www.youtube.com/watch?v=PnAMEe0GGG8&pp=ygUWdmFpIG5hbW9yYXIgY29taWdvIHNpbQ%3D%3D&t=20s";
}
</script>

</body>
</html>
