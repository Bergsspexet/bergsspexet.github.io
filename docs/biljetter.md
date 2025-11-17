# Biljetter

Köp biljetter via detta formulär: https://forms.gle/4Hn6vraZeUwg7STr7

(All aktuell infromation finns i Formuläret.)

För frågor maila oss på [bergsspexet@gmail.com](mailto:bergsspexet@gmail.com)

### Spexpremiärens nedräkning
Vi räknar ned till vår Premiär av det 82:a Bergsspexet, Lördagen den 6 december kl. 12:30 [tiden justeras eventuellt]

Biljettsläpp sker i början av november, intresse kan anmälas i detta [formulär](https://forms.gle/fQpLMaoBRRdNBK4Q7).

Föreställningen börjar om:

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <span id="weeks"></span> veckor, 
  <span id="days"></span> dagar, 
  <span id="hours"></span> timmar, 
  <span id="minutes"></span> minuter och 
  <span id="seconds"></span> sekunder.
</div>

<script>
  var targetDate = new Date("Dec 6, 2025 12:00:00").getTime();

  var countdownFunction = setInterval(function() {
    var now = new Date().getTime();
    var distance = targetDate - now;

    var weeks = Math.floor(distance / (1000 * 60 * 60 * 24 * 7));
    var days = Math.floor((distance % (1000 * 60 * 60 * 24 * 7)) / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);
    
    document.getElementById("weeks").innerHTML = weeks;
    document.getElementById("days").innerHTML = days;
    // document.getElementById("time").innerHTML = hours + ":" + minutes + ":" + seconds;
    document.getElementById("hours").innerHTML = hours;
    document.getElementById("minutes").innerHTML = minutes;
    document.getElementById("seconds").innerHTML = seconds;

    if (distance < 0) {
      clearInterval(countdownFunction);
      document.getElementById("countdown").innerHTML = "Bergslusse nedräkningen klar!";
    }
  }, 1000);
</script>
