<!-- Arquivo colisão.html-->
<html><head>
<title>exercício de colisão</title>
<script src= "gamesWeb.js"></script>
</head><body>
<canvas id="canv" width="1000" height="600">
este browser não suporta o objeto canvas do html5
</canvas>
<script>
canvas = document.getElementByld("canv")
ctx=canvas.getContext("2d");
nave=new Image();
nave.src="img/nave.png";
nave.onload=fuction(){
xNave=canvas.width/2-nave.width/2;
yNave=canvas.height-nave.height;
ctx.drawimage(nave, xNave, YNave);
}

inimigo=new Imagem();
inimigo.src="img/inimigo.png";
inimigo.onload=function(){
    xinimigo=canvas.width/2-naves.width/2;
    yinimigo=0;
    ctx.drawimage(inimigo, xinimigo, yinimigo);
}
document.addEventListener("Keydown", function(evento){
    movimentoNaveInimigo(evento.key);
});
</script>
</body></html>
//código no arquivo games.Web.js

functi