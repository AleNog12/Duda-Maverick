<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>Pedido de Namoro</title>
</head>
<body>

<h2>Quer namorar comigo?</h2>
<p>Você me faz mais feliz do que eu jamais pensei que poderia ser. Se você aceitar, clique no botão abaixo!</p>

<button onclick="showVideo()">Sim, aceito!</button>

<div id="video" style="display:none;">
  <p>Que bom que você aceitou! Aqui está nosso vídeo:</p>
  <!-- Substitua 'your_video.mp4' pelo caminho do seu vídeo -->
  <video width="320" height="240" controls>
    <source src="https://youtube.com/shorts/DM47R2-GIGM" type="video/mp4">
    Seu navegador não suporta vídeos.
  </video>
</div>

<script>
function showVideo() {
  document.getElementById('video').style.display = 'block';
}
</script>

</body>
</html>
