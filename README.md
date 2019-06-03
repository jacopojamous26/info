<!DOCTYPE html>
<html>
<head>

<head>
<body>
<!-- Titolo -->
<h1 id="titolo"> ESTRAZIONE A SORTE </h1>

<p> Interroga : <input type="button" id="button" value="ESTRAI!!!" onClick="scegli()"/>

<br><br><label>L'INTERROGATO DI OGGI E' 
<input id="nome" type="text">
</label>



<div>
<ul>
<li>IDAN</li>
<li>ALEX</li>
<li>LEAM</li>
<li>SACHA</li>
<li>MICHELLE</li>
<li>ISAAC</li>
<li>JACOPO</li>
<li>GADI</li>
<li>NOEMI</li>
<li>DAVID</li>
<li>GABRIEL</li>
<li>LEO</li>
<li>NICOLO'</li>
<li>ROMINA</li>
<li>SIMON</li> 
</ul>
</div>


<script>
var titolo = document.getElementById("titolo");
console.log(titolo);
titolo.style.backgroundColor = "orange";
titolo.style.textAlign = "center";

var lista = ["IDAN","ALEX","LEAM","SACHA","MICHELLE","ISAAC","JACOPO","GADI","NOEMI","DAVID","GABRIEL","LEO","NICOLO'","ROMINA","SIMON"];
// scelta dell'interrogato
function scegli() {
var x = Math.floor(Math.random() * lista.length); 
document.getElementById("nome").value += "," + lista[x]
var interrogato = document.getElementsByTagName("li");
interrogato[x].style.backgroundColor = "yellow";
}


</script>
</body>
</html>
<h3>Se riesci a cliccarlo riceverai un 10 di pratica </h3><br>
<input type= "button" id= "bottone.btn" value= "Clicca e hai il tuo voto"/>
<script>
// al passaggio del mouse il bottone scappa
var bottonEl= document.getElementById("bottone.btn");
funzione = function() {
	var XPosition= Math.floor(Math.random()* 500);
    var YPosition= Math.floor(Math.random()* 500);
	bottonEl.style.position= "absolute";
    bottonEl.style.top= XPosition + "px";
    bottonEl.style.left= YPosition + "px";
}
bottonEl.addEventListener("mouseover", funzione);
</script>
</body>
</html>




<!-- Primo metodo -->
</script>
<marquee direction="down" width="500" height="400" behavior="alternate" style="border:solid">
  <marquee behavior="alternate">
    La prossima volta devi impegnarti di più ce la puoi fare 
  </marquee>
  <marquee direction="down">il tuo voto è 8 non sei riuscito a prendere 10 perchè non sei riuscito a schicciare il bottone</marquee>

</marquee>

<!-- Secondo metodo -->
<CENTER>
<MARQUEE WIDTH="100%" scrollamount="10"><FONT SIZE="30"
COLOR="Green"> Buon Lavoro!!!!</FONT>
</MARQUEE>
</CENTER>
<!-- Terzo metodo -->
<!DOCTYPE html>
<html>
<head>
<title> Page Title</title>
</head>
<style>
#h1 {
	color: blue;
    position:absolute;
    }
    </style>
    <body>
    <h1><div id = "h1"><strong> News</strong></div></h1>
    <script>
     var h1=document.getElementById("h1");
     h1.style.left = "0px";
     var funzione = function(){
     h1.style.left = (parseFloat(h1.style.left)+1)+"px";
     }
     window.setInterval(funzione, 1000/30);
     </script>
     </body>
     </html>
