# Biljetter

## Du kan nu boka Grande Finale biljetter via detta [formulär](https://docs.google.com/forms/d/e/1FAIpQLSczhfdzlws5AeZsAuWBJPuDNQfdGRoDwNZlZTnBonZ5wvrZdg/viewform?usp=header)!
För frågor maila oss på [bergsspexet@gmail.com](mailto:bergsspexet@gmail.com)

Final dagarna för det 81:a Bergsspexet äger rum på Teater3 den 2:a & 3:e Maj.

Detaljer:

Fredag 2:a maj kl. 18.30

Lördag 3:e maj kl. 13.00

Insläpp 30 minuter innan

Spexet är ca 3h inklusive paus.

### Spexpremiärens nedräkning
Vi räknar ned till vår final Grand Finale av det 81:a Bergsspexet: "Det stålta Järnälvsundshotellet; ...eller en skänk från ovan." Föreställningen börjar om:

<div id="countdown" style="font-size: 1.2em; font-weight: bold; text-align: center; margin: 20px auto;">
  <span id="weeks"></span> veckor, 
  <span id="days"></span> dagar, 
  <span id="hours"></span> timmar, 
  <span id="minutes"></span> minuter och 
  <span id="seconds"></span> sekunder.
</div>


<script>
  var targetDate = new Date("May 3, 2025 13:00:00").getTime();

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
