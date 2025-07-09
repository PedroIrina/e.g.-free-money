# e.g.-free-money
<!DOCTYPE hmtl>
<html>
<head>
    <meta charset="UTF-8">
  <title>Free Money</title> 
</head> 
<body>
  
 
<!-- Premier Bouton -->
  <p>Click for free money.</p>
<button onclick="afficherMessageEtBouton()">$</button>

<!-- Message caché au départ -->
<p id="message" style="display : none;">Have you really believed in this button ?</p>
  
<!-- Deuxième bouton, caché au départ -->
<button id="SecondButton" style="display : none;"
  onclick="ActionDeux()">I trusted you...</button>

<!-- Deuxième message caché au départ -->
<p id="message2" style="display : none;">
  You shouldn't trust anyone or neither be 
  too curious... you never know what could 
  be behind the next door you open.
  Or maybe you know what's behind but you
  aren't strong enough to dodge the desire
  of opening it to see what will happen ?
  I can't blame you... It's part of being 
  human, we fight against our weaknesses, 
  therefore we must find our weaknesses to 
  work on them. Maybe we will find peace
  by defeating our weaknesses ?
  Is it even possible to kill our
  weaknesses so they never wake up again ? 
  I guess the only way to know the answer
  is to desperately struggle in this 
  lifetime strewn with pitfalls... 
  pitfalls that take one mistake to fall
  into yet it takes millions of efforts to
  climb back up to the point where you have
  fallen from... Not everyone finds the
  power of climbing back up, some people
  didn't even notice that they fell,
  some people think that it's better to
  accept their fate of falling because it
  is too hard, and a tiny part of people
  remain patient and composed :
  They understand their fall.
  They instantely think about solutions...
  but they are not a lot on Earth,
  "They" is being isolated by our 
  society made of weak people that keep on 
  falling and falling... 
  How can "They" live in a place that 
  feels like hell ? My answer is Yamina.</p>
  
<!-- Script -->
<script>
  function afficherMessageEtBouton() {
    //affiche le message
    
document.getElementById("message").style.display = "block";
    
    //affiche le deuxième bouton
    
document.getElementById("SecondButton").style.display = "inline-block";
  }
  
  function ActionDeux() {
    alert("Curiosity brought you here? Curiosity is made so weak people sin.");
document.getElementById("message2").style.display = "block";  
document.getElementById("YaminaButton").disabled = false 
  }
</script>
  
<!-- Bouton Yamina, activé au départ --> 
<button id="YaminaButton" disabled
  onclick="alert
  (`Ecrire du code est une bonne manière
  pour moi de prendre le temps de poser
  mes mots sur ce que j'ai dans le coeur, 
  je suis obligé de prendre mon temps car
  écrire ces lignes de code en demande 
  beaucoup... automatiquement ça me donne
  le temps de plonger dans mon coeur pour
  pouvoir t'exprimer mon amour et de tuer
  les idées que le sheitan essaye de faire 
  rentrer dans ma tête, en vain car tu me
  rassures et me montre comment le
  combattre... InchaAllah tu seras au
  Paradis pour me donner les armes contre
  le sheitan car il ne manque plus que ce
  combat entre moi et moi pour que je sois
  en paix avec moi même.`)">Yamina</button>  
 
</body>
</html>